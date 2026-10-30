# 우리 동네 발명 지도

초등학교 4~6학년 「지역사회를 변화시키는 발명」 4차시 수업용 웹앱입니다.
가상의 발명마을에서 불편함을 찾고 → 원인·사용자를 분석하고 → 아이디어를 내어 고르고 → 설계·제작·시험·개선한 뒤 → A4 발명 제안서로 인쇄합니다.

- 빌드 과정 없는 정적 페이지 하나(`index.html`)로 동작합니다.
- 로그인·서버·지도 API·AI API를 쓰지 않습니다.
- 기록은 브라우저 localStorage에 자동 저장됩니다(저장 칸 3개). 다른 기기에서 이어 하려면 JSON 활동 파일로 저장·불러오기를 합니다.

## 배포 (Vercel)

1. Vercel에서 **Add New → Project**로 이 저장소를 가져옵니다.
2. Framework Preset은 **Other**, Build Command와 Output Directory는 비워 둡니다.
3. **Deploy**를 누르면 루트의 `index.html`이 그대로 서비스됩니다.

로컬에서는 `index.html`을 크롬·엣지로 바로 열어도 됩니다.
