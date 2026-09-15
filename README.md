# Girl Group Debut Teaser (Demo)

5인조 걸그룹 데뷔 티저 페이지 데모입니다. 데뷔일(2026-12-30)까지 실시간 카운트다운을 보여줍니다.

## 로컬에서 실행하기

이미지 파일이 없어도 카운트다운 페이지는 정상 동작합니다. 원하는 이미지를 `teaser.png`로 저장해 프로젝트 루트에 넣으면 히어로 이미지가 표시됩니다.

```bash
git clone https://github.com/byoungheekim/girlgroup-debut-teaser.git
cd girlgroup-debut-teaser
python3 -m http.server 8000
```

브라우저에서 http://localhost:8000 접속

## 파일 구조

- `index.html` - 메인 페이지
- `style.css` - 스타일
- `script.js` - 카운트다운 로직
- `teaser.png` - 히어로 이미지 (직접 추가 필요)
