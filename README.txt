# 삼국지 인물 성향 테스트 배포용 패키지

포함 파일
- index.html : 테스트 본문
- og-image.svg : 카카오톡/메신저 링크 미리보기용 이미지
- README.txt : 배포 방법

배포 방법
1. index.html과 og-image.svg를 같은 공개 웹 경로에 업로드합니다.
   예: https://your-domain.com/sanguo/index.html
       https://your-domain.com/sanguo/og-image.svg

2. index.html 안에서 아래 문자열을 실제 주소로 바꿉니다.
   https://YOUR-DOMAIN.example/sanguo/

3. 카카오톡으로 index.html 주소를 공유합니다.

메모
- 일반적인 링크 썸네일은 Open Graph 메타태그로 동작합니다.
- 카카오톡의 링크 미리보기 캐시 때문에 수정 후 반영이 늦을 수 있습니다.
- 이 패키지는 '링크 공유용' 준비본입니다.
- 카카오 SDK 버튼까지 붙인 완전한 커스텀 공유형으로 가려면 별도 앱 키 설정이 필요합니다.
