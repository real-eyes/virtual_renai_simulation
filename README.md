# virtual_renai_simulation
능동형 미연시를 하기위한 데이터셋 개념, sLM에 학습할 데이터셋 구조에 대한 간단한 설명

## 기존 구조 (작성 중)
- Persona: 여기서 말하는 페르소나란, 미연시의 '캐릭터'를 의미.
  - 단, 여기서는 일단 다루지 않음.
- likeability: 호감도로 미연시를 진행할 때 결말에 도달하기 위한 임계치

## Dataset
- Persona(Option): 특정 캐릭터
- System: 호감도(likeability)에 따라 상황 변경을 하기 위한 값
- input: 주인공(사용자)가 입력한 값
- Output: input에 대하여 가상여친의 답에 대한 기대값
- ChangeSystem: System(호감도)를 변경하기 위한 값
