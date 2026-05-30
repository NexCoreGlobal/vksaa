# 베한 유학협회 웹사이트
**Viet-Korea Study Abroad Association**

---

## GitHub Pages 배포 (3단계)

1. GitHub에서 새 저장소 생성
2. 이 폴더 파일 전체 업로드
3. Settings → Pages → Branch: main → Save
4. `https://계정명.github.io/저장소명` 으로 접속

---

## 폴더 구조

```
vietkoreaedu/
├── index.html        ← 메인 페이지 (모든 코드 포함)
├── images/
│   ├── slide1.jpg    ← 슬라이드 1 배경 이미지 교체용
│   ├── slide2.jpg    ← 슬라이드 2 배경 이미지 교체용
│   ├── slide3.jpg    ← 슬라이드 3 배경 이미지 교체용
│   ├── news1.jpg     ← 뉴스 카드 1 이미지 (선택)
│   ├── news2.jpg     ← 뉴스 카드 2 이미지 (선택)
│   └── news3.jpg     ← 뉴스 카드 3 이미지 (선택)
├── files/            ← 다운로드 파일 저장
└── pages/            ← 서브 페이지 (추후 추가)
```

---

## 콘텐츠 수정 방법 (코딩 불필요)

### 슬라이드 이미지 교체
`images/` 폴더에 아래 파일명으로 사진을 넣으면 자동 적용됩니다.
- `slide1.jpg` / `slide2.jpg` / `slide3.jpg`
- 권장 크기: **1400 × 600px** 이상

### 뉴스 카드 수정
`index.html` 에서 `var NEWS = [` 부분을 찾아 수정

### 공지사항 수정
`index.html` 에서 `var NOTICES = [` 부분을 찾아 수정

### 자료실 파일 추가
1. `files/` 폴더에 파일 업로드
2. `index.html` 에서 `var FILES = [` 부분에 항목 추가

---

© 2025 베한 유학협회
