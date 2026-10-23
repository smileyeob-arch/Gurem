구름날씨 개인용 웹앱
=====================

구성
- index.html: 앱 본체
- manifest.webmanifest: 홈 화면 설치용 메타데이터
- sw.js: 기본 파일 캐시

기능
- Windy 삽입 지도: 강수/구름/바람/기온 레이어 선택
- Open-Meteo: 현재 조건, 시간별 예보, 7일 예보
- 대전/서울/부산/도쿄/오사카 지역 전환

중요한 제한
- 예보는 Open-Meteo 데이터이며 Windy의 예보 API 데이터가 아닙니다.
- Open-Meteo 무료 API는 개인·비상업 용도 기준이며, 표시된 출처 링크를 유지하세요.
- Windy 지도는 Windy 삽입 서비스를 사용합니다. 해당 서비스의 기능/이용 조건이 변경될 수 있습니다.
- 인터넷 연결이 필요합니다. 로컬 파일로 직접 열면 브라우저 보안정책상 예보 API나 설치 기능이 제한될 수 있습니다.
- 홈 화면 설치(PWA)를 제대로 사용하려면 HTTPS로 호스팅해야 합니다.

스마트폰에서 사용하는 방법
1. ZIP 압축을 풉니다.
2. index.html을 HTTPS 정적 호스팅에 올립니다. 예: GitHub Pages 또는 Netlify.
3. 생성된 HTTPS 주소를 갤럭시 Chrome에서 엽니다.
4. Chrome 메뉴(⋮) → '홈 화면에 추가' 또는 '앱 설치'를 선택합니다.

API 비용
- Open-Meteo: 개인·비상업 이용은 무료 API 정책 적용(공정 사용 및 출처 표시 조건).
- Windy Map Forecast API 정식 키는 이 버전에 필요하지 않습니다. Windy 지도 삽입 기능을 사용합니다.
- Windy 공식 API를 직접 사용하거나 공개·상업 서비스로 확장하려면 최신 라이선스/가격을 다시 확인하세요.

참고 링크
- Windy 지도 삽입: https://embed.windy.com/
- Windy API 요금: https://api.windy.com/map-forecast/pricing
- Open-Meteo: https://open-meteo.com/
