# 캐릭터 이미지 넣는 법

1. 파일 이름은 아래 id를 그대로 씁니다: `confucius.png`
   - confucius(공자), mencius(맹자), buddha(석가모니), laozi(노자), zhuangzi(장자)
   - socrates(소크라테스), plato(플라톤), aristotle(아리스토텔레스), kant(칸트), mill(밀), rawls(롤스)
2. 형식: 투명 배경 PNG. 정사각형 프레임(예: 96×96)을 가로로 이어 붙인 한 장.
   - 프레임 1개(정지 이미지)도 되고, 2~4개면 앱에서 반복 재생됩니다.
3. 이 폴더에 PNG를 올린 뒤 `manifest.json`에 id를 적습니다.
   - 예: `["confucius", "socrates"]`
4. 목록에 없는 철학자는 기본 임시 캐릭터로 나옵니다.
