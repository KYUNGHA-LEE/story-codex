# 동화책 프롬프트 생성 웹앱 V7

AI 인터뷰 → 줄거리 → 캐릭터 참조 이미지 프롬프트 → 페이지별 원고 → 장면별 최종 이미지 프롬프트를 Gemini API로 자동 생성하는 단일 HTML 웹앱입니다.

- 서버 없이 `index.html` 하나로 동작합니다.
- Gemini API 키는 [키 저장]에서 사용자가 동의한 경우에만 브라우저(localStorage)에 저장되며, [저장 삭제]로 바로 지울 수 있습니다.
- 작업 내용은 워드(.doc) 또는 작업 파일(.json)로 저장하고 다시 불러올 수 있습니다.
- Gemini API 키 발급: https://aistudio.google.com/apikey

made by 이경하
