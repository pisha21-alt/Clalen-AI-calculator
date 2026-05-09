# Clalen CL Calculator — PWA 배포 가이드

## 📁 파일 구조
```
clalen-pwa/
├── index.html          ← 메인 앱
├── manifest.json       ← PWA 설정
├── sw.js               ← 서비스 워커 (오프라인 지원)
└── icons/
    ├── icon-192.png    ← 앱 아이콘 (Android)
    ├── icon-512.png    ← 앱 아이콘 (스플래시)
    └── apple-touch-icon.png ← 앱 아이콘 (iPhone)
```

---

## 🚀 무료 배포 방법 (GitHub Pages — 추천)

### 1단계: GitHub 계정 만들기
→ https://github.com/signup (이미 있으면 Skip)

### 2단계: 새 저장소 만들기
1. github.com 로그인 → 우측 상단 `+` → `New repository`
2. Repository name: `clalen-rx` 입력
3. Public 선택 → `Create repository`

### 3단계: 파일 업로드
1. `Add file` → `Upload files` 클릭
2. clalen-pwa 폴더 안의 **모든 파일** 드래그 업로드
   - index.html
   - manifest.json
   - sw.js
   - icons/ 폴더 전체
3. `Commit changes` 클릭

### 4단계: Pages 활성화
1. 저장소 상단 `Settings` 탭
2. 좌측 `Pages` 메뉴
3. Source: `Deploy from a branch`
4. Branch: `main` / `/ (root)` 선택 → `Save`
5. 1~2분 후 URL 생성됨:
   **https://[내github아이디].github.io/clalen-rx/**

### 5단계: 배포 완료!
→ 생성된 URL을 카카오톡, 문자로 안경사에게 공유

---

## 📲 안경사가 앱으로 설치하는 방법

### Android (크롬 브라우저)
1. URL 접속
2. 상단 배너 "설치" 버튼 탭 (또는 우측 상단 ⋮ → "앱 설치")
3. 홈 화면에 아이콘 추가됨

### iPhone (Safari 브라우저)
1. **Safari**로 URL 접속 (크롬 불가)
2. 하단 공유 버튼 탭 (□↑)
3. "홈 화면에 추가" 선택
4. "추가" 탭

---

## ✅ 특징
- 인터넷 없어도 작동 (오프라인 지원)
- 업데이트 시 파일만 교체하면 모든 사용자에게 자동 반영
- 앱스토어 심사 불필요
- 무료 호스팅
