# 동화책 프롬프트 생성기

줄거리 → 캐릭터 고정 명세 → 페이지별 원고 → 장면 이미지 프롬프트를 Gemini API로 4단계 자동 생성하는 단일 HTML 웹앱입니다.

- 서버 없이 `index.html` 하나로 동작합니다. API 키는 사용자 동의 시에만 브라우저(localStorage)에 저장됩니다.
- 작업 내용은 워드(.doc) 또는 JSON으로 저장하고, JSON은 다시 불러올 수 있습니다.
- Gemini API 키 발급: https://aistudio.google.com/apikey

made by 이경하 · Claude 수정 2026.09.17
