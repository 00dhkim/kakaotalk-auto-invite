# kakaotalk-auto-invite
일일이 친구추가하고, 톡방 초대하고... 너무 힘들다! 자동으로 톡방 만들어주는 스크립트를 짜보자!

## 현재 조사한 내용
- PC카톡에서는 전화번호로 사용자 검색 안됨 (모바일은 가능)
- 전화번호로 친구 추가 시 이미 있는 사용자면 팝업 하나 나타났다 사라짐
- 채팅방에 초대를 하려면 무조건 친구여야 함

## 방법
- 방법1. 전화번호만 있을 때, 명단의 모든 인원을 친구추가 후 모두 초대함. 이때 원래 친추되어있는 인원인 경우 예외처리 필요
- 방법2. 이름을 모두 알고 있고 모두 친추되어있을 때, 이름만으로 톡방 초대함. 이때 동명이인이 있으면 어떻게 처리할 것인지 정할 필요 있음. 그리고 사용자가 이름 본명으로 안해놓으면 예외처리 필요.
  - 폰에서 수동으로 연락처 추가하면 카톡에도 갱신되는 기능을 써야 함.

## 참고자료
win32 API 관련
- https://dev-guardy.tistory.com/21
- https://airfox1.tistory.com/2
- https://www.vbflash.net/180

카카오톡 자동 친구추가 관련
- https://evols-atirev.tistory.com/23 
- https://fecohero.tistory.com/entry/%EA%B5%AC%EA%B8%80-%EC%8A%A4%ED%94%84%EB%A0%88%EB%93%9C%EC%8B%9C%ED%8A%B8-%EC%86%8D-%EC%97%B0%EB%9D%BD%EC%B2%98-%EC%95%84%EC%9D%B4%ED%8F%B0%EC%9C%BC%EB%A1%9C-%EA%B0%80%EC%A0%B8%EC%98%A4%EA%B8%B0

