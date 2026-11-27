# PRJ-0015 설문 결과 자동 리포트 산출물

작성일: 2026-11-27 / 버전: v1.0

## 파일
- PRJ-0015_UI-설계서_v1.0.docx
- PRJ-0015_기능정의서_v1.0.docx
- PRJ-0015_API-설계서_v1.0.docx
- PRJ-0015_디자인-시스템_v1.0.docx
- 모바일 컨셉 디자인 시안용.html

## 프로젝트 기준
현재 GitHub 저장소의 main 브랜치는 Python 로컬 CLI입니다. CSV 검사, 열 유형 판별, 숫자/선택형 통계, 주관식 단어 빈도, 개인정보 의심 열 기본 제외, HTML/SVG 및 PDF 생성 기능을 기준으로 문서를 작성했습니다.

로그인, 결제, SaaS 웹/API 서버, 사용자별 클라우드 저장은 현재 구현 범위가 아닙니다. API 설계서의 REST 경로는 모바일 연동을 위한 제안 초안이며 실제 구현 엔드포인트가 아닙니다.

HTML은 화면 이동과 브라우저 내 CSV 미리보기/HTML 다운로드/인쇄를 제공하는 독립 UX 프로토타입입니다. Python CLI와 직접 연결되어 있지 않으며, 기존 엔진의 실행 결과를 대체하지 않습니다. 실제 모바일 제품으로 연결하려면 API 또는 로컬 브리지 구현이 필요합니다.

## 실행
HTML 파일을 브라우저에서 열어 홈 → 가져오기 → 검사 → 보고서 → 설정 흐름을 확인합니다. 샘플 데이터로 체험하거나 CSV 파일을 선택할 수 있습니다.

## 참고
- https://github.com/jeong-jihyun/survey-auto-report-saas
- https://github.com/jeong-jihyun/goodnotes-digital-planner/tree/main/docs
- https://github.com/jeong-jihyun/google-sheets-template-shop/tree/main/docs
- https://github.com/jeong-jihyun/kakao-emoticon-studio/tree/main/docs
- https://www.figma.com/ko-kr/community/mobile-apps?resource_type=files&editor_type=figma
