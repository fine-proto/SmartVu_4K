# SmartVu 4K · Web Demo

SmartVu 4K 앱(Android)을 실제 블랙박스 없이 브라우저에서 시연하기 위한 웹 프로토타입입니다. (`index.html` 단일 파일)
파인뷰 Wi-Fi 앱 웹 데모와 같은 구성에 SmartVu 스킨(모노톤 컬러·로고·아이콘)과 문구를 적용했습니다.

- 시연 모델: **SmartVu 4K** 1종 (NON-LCD · Wi-Fi 목록에서 직접 연결, Wi-Fi 이름 `SmartVu_4K_xxxx`)
- 가상 동작: 연결(REC 버튼 페어링), 재생 모드·설정 메뉴 진입 시 녹화 중지/재개, 녹화 방식 변경·설정 초기화·펌웨어 업데이트 후 재부팅, 단말 언어·스피드캠 지역 선택
- 개인정보 처리방침: https://motoronegroup.com/privacy-policy/ (한국어/영어 공통, 데모 모바일 화면 안에서 열림)
- 언어: 한국어 / English. PC에서는 왼쪽 데모 패널, 휴대폰에서는 오른쪽 아래 `DEMO` 버튼으로 바꿉니다. 영어로 바로 열려면 주소 끝에 `?lang=en`을 붙이세요.
- 영상 상단 OSD의 'FineVu X550' 부분은 영상 위에 검정 마스크를 씌워 'SmartVu'로 표시합니다. (영상 파일 자체는 원본 그대로)
- 영상: `video/front.mp4`, `video/rear.mp4` (샘플 영상). `index.html`과 `video` 폴더를 함께 두어야 재생됩니다.

## 웹으로 보기 (GitHub Pages)
Settings → Pages → Deploy from a branch → `main` / `(root)` → Save
→ https://fine-proto.github.io/SmartVu_4K/
