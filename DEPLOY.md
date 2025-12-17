# GitHub Pages 배포 가이드

## 배포에 필요한 파일

GitHub Pages 배포를 위해 다음 파일만 필요합니다:

- `index.html` - 메인 HTML 파일 (필수)
- `.gitignore` - 이미지 파일 제외 설정 (선택)
- `README.md` - 프로젝트 설명 (선택)

## 배포 방법

### 1. GitHub 저장소 생성
- 저장소 이름: `Dollar`
- 저장소 URL: `https://github.com/SynItArt/Dollar`

### 2. 파일 업로드
```bash
cd "D:\ConsultingMaster\03_특화서비스\달러\Deploy"
git init
git add index.html .gitignore README.md
git commit -m "Initial commit: 달러보험 가입 제안서"
git branch -M main
git remote add origin https://github.com/SynItArt/Dollar.git
git push -u origin main
```

### 3. GitHub Pages 활성화
1. GitHub 저장소로 이동
2. Settings > Pages 클릭
3. Source: Deploy from a branch 선택
4. Branch: main 선택
5. Folder: / (root) 선택
6. Save 클릭

### 4. 배포 확인
- 몇 분 후 `https://synitart.github.io/Dollar/` 에서 확인 가능

## 주의사항

- 이미지 파일은 저작권 문제로 제외되었습니다
- 모든 이미지 참조는 제거되었습니다
- 사이트는 이미지 없이도 정상 작동합니다

