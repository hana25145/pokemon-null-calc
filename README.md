# Pokémon Null Damage Calculator

Pokémon Null 롬핵용 데미지 계산기입니다. `index.html` 파일 하나로 작동합니다.

- Null 변경사항 반영: 기술 위력·타입·명중 변경표, 대폭발/자폭/미스트폭발, 잠재파워 위력 60, 필드 강화 1.5배, 마비 스피드 −75%, 리프가드·마그마의무장 급소 무효
- 모든 트레이너 팀(380명) 내장. Pokémon 2 칸에 `포켓몬 (트레이너 이름)`을 입력해 불러옵니다.
- Null AI 문서의 점수 규칙으로 AI가 고를 기술 확률, 교체 확률, 다음에 나올 포켓몬을 시뮬레이션합니다 (싱글 배틀 기준).
- Null Lua 스크립트의 Showdown 형식 내보내기를 Import / Export 칸에 붙여넣어 내 포켓몬을 가져올 수 있습니다.

데미지 계산은 [@smogon/calc](https://github.com/smogon/damage-calc) (MIT)를 사용합니다. 스프라이트는 Pokémon Null 자료의 Dex 시트에 있는 이미지 주소(Pokémon Showdown 등)를 그대로 불러옵니다. 트레이너·기술 데이터는 Pokémon Null 커뮤니티 자료에서 가져왔습니다.
