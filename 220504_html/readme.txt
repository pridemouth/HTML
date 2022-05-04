<html>

positioning

	position: ___;
		static - 문서 흐름에 맞춰 배치(default).
			top left right bottom으로 위치 지정 불가.
			float right, left만 가능.
		relative - 이전 요소에 자연스럽게 연결해 배치
			top left right bottom으로 위치 지정 가능은 하나 권장하지 않음.
			음수값 지정 시 원점에서 들여서 배치함.
		absolute - 부모 요소의 범위 안에서, 원하는 위치 지정
		fixed - window 기준으로 고정(부모 요소와 무관하게 위치값이 정해짐)
	
	z-index: ___;
		z-index가 큰 쪽(숫자)이 위로 올라옴.
		z-index가 동일한 경우에도, 개체가 생성된 시기에 따라서 순서가 정해질 수 있음.
	
	visibility
	
	
	<!-- window의 원점은 좌상단 -->
	<!-- margin에 수치 두 개 입력 시, 상하 좌우 margin으로 취급됨 -->