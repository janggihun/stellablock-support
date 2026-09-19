# 스텔라블록 — 지원 페이지

Google Play 의 **사용자 데이터 삭제** 정책이 요구하는 안내 페이지다.

- 공개 주소: https://janggihun.github.io/stellablock-support/
- Play 콘솔 ▸ 앱 콘텐츠 ▸ 데이터 보안 에 위 주소를 등록한다

앱 쪽 삭제 경로는 **설정 ▸ 계정 ▸ 게임 탈퇴** 이고,
서버에서는 `delete_my_account()` 가 `auth.users` 행을 지우면
연쇄 삭제로 `players` · `scores` · `game_sessions` 까지 함께 사라진다.

> ⚠️ 앱의 삭제 경로가 바뀌면 `index.html` 의 설명도 같이 고친다.
> 심사에서 **화면과 안내가 다르면** 걸린다.
