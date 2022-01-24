﻿# JS_homework
-JavaScript 교육 과제 [장바구니 페이지 작성 조건]   

 공통 : 더하기 빼기 와 같이 여러군대서 중복 사용이 가능한 기능은 함수로 만들어서 이용한다.  
 
0. 품절.  
	0.0 첫번째 상품을 품절로 처리한다.  
	0.1 상품이 품절일 경우 품절 상태로 표현 한다.  
	0.1.1 주문 금액 영역에서 가격을 제거하고 품절 상태로 표현.  
	0.2 품절일 경우 0으로 표현하고, 수량 조절 버튼 및 input 박스를 disabled 처리 한다.  
1.수량  
	1.1 수량은 더하거나 빼기가 가능 해야 한다.  
	1.2 각 항목당 수량은 최대 30개 최하1까지 조절 가능 하다.(3개 상품 동일)  
	1.3 30개 이상이거나 1개 이하일 때 경고 메세지 출력 후 기존 값이 변화가 없어야 한다.  
    		1.3.1 최대 수량을 넘을 경우 [최대 수량입니다.]  
    		1.3.2 최소 수량을 넘을 경우 [최소 수량입니다.]  
              1.4 수량 변경 후 [변경]버튼을 누르면 변경한 수량만큼 가격 정보가 변경 되어야 한다.  
		1.4.1 바로 옆 [주문 금액]컬럼이 변경된 갯수만큼 주문 가격 정보가 나와야 한다.   
		1.4.1 하단 회색 행에 [주문금액 :619,150원 + 배송비합계 :6,000원 = 총 예상 결제금액679,150원 ] 항목도 변경된 수량 만큼 정보를 갱신한다.  
2. 선택  
              2.1 전체 선택 체크 하면 모든 상품 체크박스가 선택된 상태로 나와야 하며 체크 해제 하면 모든 상품이 체크 해제된 상태가 되어야 한다.  
	2.2 각 상품 항목마다 체크박스로 선택 후 주문 삭제 버튼 클릭으로 상품 제거.  
              2.2.1 각 행마다 주황색 버튼으로 있는 주문하기 밑에 삭제하기 버튼 클릭시 해당 열의 상품만 제거.  
              2.2.2 선택 상품을 삭제 버튼을 클릭시 선택 된 상품을 모두 제거  

3.주문   
	3.1 검정 색 버튼 [주문 하기] 클릭시 선택 된 행에 관련된 데이터 출력.  
	    설명 : input 테그의 name 이 qty,amt,deliver_amt,goods_code,item_no 인것을 출력한다.  
              3.2 실제 결제 금액도 출력 되어야 한다.  

[  
	{  
		qty :   
		amt:  
		deliver_amt  
		....  
	},  
	{  
		qty :   
		amt:  
		deliver_amt  
		....  
	}  
],  

주문 가격 : 선택된 상품 주문 가격 출력.  
  
