# GitHub Pages 배포용 파일 목록

## 업로드할 파일 (최소 필수)

다음 파일만 GitHub 저장소에 업로드하세요:

1. **index.html** - 메인 HTML 파일 (필수)
2. **README.md** - 프로젝트 설명 (선택)
3. **.gitignore** - 불필요한 파일 제외 설정 (선택)

## 업로드하지 않을 파일

다음 파일들은 업로드하지 마세요:

- 달러-업업업.html
- 달러-제안.html
- 달러-복사본.html
- 달러전략.md
- 달러전략 - 인플레이션.html
- 달러전략 - 인플레이션.txt
- 모든 PDF 파일
- 모든 PPTX 파일
- 모든 이미지 파일
- 기타 문서 파일들

## 빠른 배포 명령어

```bash
cd "D:\ConsultingMaster\03_특화서비스\달러\Deploy"
git init
git add index.html README.md .gitignore
git commit -m "Initial commit: 달러보험 가입 제안서"
git branch -M main
git remote add origin https://github.com/SynItArt/Dollar.git
git push -u origin main
```

## GitHub Pages 활성화

1. GitHub 저장소 Settings > Pages
2. Source: Deploy from a branch
3. Branch: main
4. Folder: / (root)
5. Save

## 배포 URL

배포 완료 후: `https://synitart.github.io/Dollar/`

