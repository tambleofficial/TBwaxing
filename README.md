# TB왁싱 전국 홈페이지 (정적 사이트)

## 배포 (GitHub → Cloudflare Pages)
1. 이 폴더 안의 파일 전체를 GitHub 저장소 루트에 올립니다. (index.html이 루트에 있어야 함)
2. Cloudflare Pages → 프로젝트 생성 → GitHub 저장소 연결
3. 프레임워크: 없음 / 빌드 명령: 비워둠 / 출력 디렉터리: /
4. 커스텀 도메인 tbwaxing.co.kr 연결

## 수정 위치
- 전화번호·카톡 주소: index.html, 404.html 에서 010-3901-2337 / pf.kakao.com/_QqyKn 검색
- 색상·글꼴: assets/css/style.css 상단 :root
- 첫 화면 이미지: assets/images/hero.jpg 교체 (마케팅 문의 문구가 들어간 완성 이미지)
- 공간 사진: assets/images/space-1~3.jpg 교체

## 페이지 목록
- / (메인), /service/ (왁싱 안내), /service/brazilian/, /service/male-brazilian/, /service/sugaring/, /service/pregnancy/
- /find/ (지점 찾기), /first-visit.html, /process/, /space/, /faq/, /contact/

## RSS
- https://tbwaxing.co.kr/rss.xml → 네이버 서치어드바이저 > 요청 > RSS 제출에 등록
- 새 페이지를 만들면 rss.xml 에 <item> 추가, sitemap.xml 에 <url> 추가

## 지역 페이지 추가 시
- /seoul/gangnam/index.html 처럼 폴더를 만들고 sitemap.xml 에 URL 추가
- 아직 없는 주소는 404.html(준비 중 안내)로 연결됩니다.

## 사진 출처 (Unsplash 라이선스, 실제 지점 사진으로 교체 권장)
- hero.jpg: Atikah Akhtar
- space-1.jpg, space-3.jpg: visualsofdana
- space-2.jpg: Cherosi
