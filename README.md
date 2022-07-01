# -input-
 input 한글입력 막기
 
 
 
 [JavaScript][사용자함수] input 한글입력 막기
								JavaScript/사용자함수 
								2017. 2. 24. 14:08
								
							

							
								// 한글입력막기 스크립트$(".not-kor").keyup(function(e) { 	if (!(e.keyCode >=37 && e.keyCode<=40)) {		var v = $(this).val();		$(this).val(v.replace(/[^a-z0-9]/gi,''));	}});/* ie 한글입력방지 css */.not-kor {	ime-mode:disabled; }
출처: https://mylife365.tistory.com/330 [변화에 적응하기:티스토리]
