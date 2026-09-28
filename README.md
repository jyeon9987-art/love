# 톨 💌

고민·카톡 대화 기반 재회 분석 서비스 (무료 · 광고 수익 모델)

## 동작 방식
1. 방문자가 고민 유형을 고르고 상황·카톡 대화·MBTI·이메일을 입력해 신청
2. 브라우저에서 **자동 분석 초안**을 만들어 Formspree로 운영자 메일에 전송
3. 운영자가 메일에서 초안을 검토·수정한 뒤 **답장**하면 신청자에게 결과 발송
   (신청자 이메일이 reply-to로 설정됨)

## 설정
- `index.html`의 `FORM_ENDPOINT`에 Formspree 폼 주소 입력 (예: `https://formspree.io/f/xxxxxxx`)
- 광고: `index.html`의 "광고 자리" 3곳에 Google AdSense 코드 삽입
- 운영자 연락처: tooolllie@gmail.com

## 기술
- HTML / Tailwind CSS (CDN) / Vanilla JS, 단일 정적 페이지
- GitHub Pages 배포, 폼 전송은 Formspree (무료 플랜 월 50건)
