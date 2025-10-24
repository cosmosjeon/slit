# SL-IT Landing Page

SL-IT의 공식 랜딩 페이지입니다.

## 프로젝트 구조

- `index.html` - 메인 진입점 (0068.html로 리다이렉트)
- `0068.html` - 메인 랜딩 페이지
- `images/` - 이미지 리소스
- `vercel.json` - Vercel 배포 설정

## 로컬 개발

```bash
# 의존성 설치
npm install

# 로컬 서버 실행
npm start
```

## Vercel 배포

```bash
# Vercel CLI 설치
npm install -g vercel

# 배포
vercel

# 프로덕션 배포
vercel --prod
```

## 섹션 구성

1. **Hero** - 메인 비디오 섹션
2. **Manifesto** - 회사 철학
3. **Works** - 프로젝트 소개 (FAXI, TREEDI, ANYON)
4. **Process** - 작업 프로세스
5. **Team** - 팀원 소개
6. **Contact** - 연락처

## 기술 스택

- HTML5
- Tailwind CSS
- GSAP (애니메이션)
- Lenis (스무스 스크롤)
