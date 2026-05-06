# 한국 TV 온에어 앱

GitHub Pages에 올려서 휴대폰에서 앱처럼 쓰는 국내 TV 온에어 바로가기 앱입니다.

## 파일 구성

- `index.html` : 앱 본문
- `manifest.webmanifest` : 모바일 홈 화면 추가용 설정
- `service-worker.js` : 앱 껍데기 캐시
- `icon.svg` : 앱 아이콘

## 배포 방법

1. GitHub에서 새 저장소를 만듭니다. 예: `korea-tv-onair`
2. 이 폴더 안의 파일 4개를 저장소 최상단에 업로드합니다.
3. 저장소 `Settings` → `Pages`로 갑니다.
4. Source를 `Deploy from a branch`로 선택합니다.
5. Branch를 `main` / `/root`로 선택하고 Save 합니다.
6. 표시되는 Pages 주소로 접속합니다.

## 휴대폰에서 앱처럼 쓰기

### 아이폰 Safari
1. Pages 주소 열기
2. 공유 버튼
3. `홈 화면에 추가`

### 안드로이드 Chrome
1. Pages 주소 열기
2. 오른쪽 위 점 3개
3. `홈 화면에 추가`

## 주의

이 앱은 방송 영상을 직접 재송출하지 않습니다.
각 방송사의 공식 온에어, 공식 라이브, 공식 유튜브 채널로 연결합니다.
