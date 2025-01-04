
순서: 

	1. 써야 할 에셋 찾기(배경, 캐릭터, 적, 아이템)

	2. 배경 구현

	3. 메인 캐릭터의 기본적인 움직임, Animator, 기본공격, 히트박스 구현

	4. 카메라 구현(캐릭터를 따라다니는 카메라)

	5. 맵 짧게 구현

	6. GUI의 캐릭터의 HP

	7. 적의 기본적인 움직임, Animator, 기본공격, 히트박스, 메인 캐릭터 감지

	8. 메인 캐릭터가 주는 데미지 구현, 적이 주는 데미지 구현

	9. 메인 캐릭터의 HP회복 구현

	10. 적의 아이템 드랍

	11. GUI의 마석에 개수 구현

	12. GUI의 캐릭터의 맞았을 때와 힐이 瑛 때의 글씨 구현

	13. 힐 아이템과 스킬 아이템 구현

	14. 컷신 구현

	15. 대사 구현

	16. 메인 캐릭터가 스킬이 있다는 것을 띄우는 GUI 구현

	17. 적이 메인 캐릭터를 발견 했다는 것에 대한 GUI 구현

	18. 메인 캐릭터의 스킬 구현

	19. 적의 스킬 구현

	20. 전투 구현(산나비 처럼 적을 전부 죽여야만 나아갈 수 있도록)

	21. GUI의 ESC창과 첫 게임 창 구현

	22. Adio 구현(전투, 비전투, 공격, 아이템 등 전부)

	23. 맵 전부 구현

	24. 보스 구현(전부)

	25. 엔딩 구현

	26. 최적화

그룹:
	
	배경:
	1. 뒷 배경 구현
	2. 캐릭터와 상호작용이 되는 땅의 기본 구현
	3. 맵 구현

	카메라:
	1. 캐릭터를 따라 다니는 카메라 구현
	2. 컷 신이 진행 될 때의 카메라 구현

	캐릭터:
	1. 메인 캐릭터 Animator에 기본적인 움직임(ex: Idle, Walk, Run, Jump등)
	2. 메인 캐릭터의 기본 공격 구현(좌클릭의 기본적인 공격과 점프 했을 때의 공격)
	3. 메인 캐릭터가 스킬을 쓸 때의 Animator 구현
	4. 메인 캐릭터의 히트박스, 공격 히트박스
	5. 메인 캐릭터가 주는 데미지 구현
	6. 메인 캐릭터가 받는 힐의 구현
	|
	1. 적의 기본적인 Animator 구현(움직임 등)
	2. 적의 움직임 구현(산나비, 스컬의 적 움직임)
	3. 적의 기본 공격
	4. 적의 스킬 공격(모두에게 있는 공격은 아니다)
	5. 적의 아이템 드랍(적을 잡았을 때의 아이템 드랍)
	6. 적의 히트박스
	7. 적의 메인 캐릭터의 확인 범위
    8. 적이 주는 데미지 구현

	아이템:
	1. 힐 아이템(캐릭터와 상호작용이 됬을 때 캐릭터의 HP가 회복이 된다)
	2. 스킬 아이템(캐릭터가 일정 이상의 드랍 템을 모았을 때 얻어진다)

	GUI:
	1. 캐릭터의 HP를 눈에 보이게 띄움
	2. 캐릭터의 스킬을 눈에 보이게 띄움
	3. 메인 캐릭터의 마석 개수 구현
	4. 데미지에 대한 공격을 받았다는 글씨 구현
	5. 힐에 대한 HP가 회복 되었다는 글씨 구현
	6. 적이 메인 캐릭터를 발견 했을 때의 글씨 구현
	7. ESC를 눌렀을 때 나오는 화면(계속하기, 나가기, 옵션 등 [이 때는 게임이 멈춰야 한다])
	8. 게임을 처음 켰을 때의 화면(새 게임, 이어하기, 옵션 등)

	Adio:
	1. 아무것도 하지않고 있을 때의 오디오 구현
	2. 공격, 움직임, 맞을 때 등의 오디오 구현
	3. 전투 할 때의 오디오 구현

	에셋:
	1. 배경
	2. 캐릭터
	3. 적
	4. 아이템
	5. 오디오

	전투:
	1. 잠겨있는 전투(적을 전부 잡기 전까지 나가지 못하게 막는 전투방식)
	2. 가능 하다면 적을 전부 잡으면 다시 적이 생기는 2페이지 같은 느낌으로


2025-01-04

오늘 할 일
1. 해야 할 작업들 나열
2. 작업들 정리
3. 캐릭터의 오른쪽과 왼쪽의 움직임
4. 캐릭터가 적과 만났을 때의 데미지 체크 
5. Slider만들기

잘 풀리지 않은 일
1. 혼자 해 보는 것은 처음 이기 때문에 코드들이 익숙치 않아서 코드를 짜는 것이 힘들었다.
2. 해야 할 작업들을 정리 하는 것 또한 처음 이기에 힘들었다.





