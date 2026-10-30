# ROAM

내 주변 명소를 지도에서 발견하고, 방문 체크인으로 경험치와 도감을 쌓는 위치 기반 탐험 웹 프로토타입이에요. (단일 `index.html`)

## 실행
1. `index.html`의 `YOUR_GOOGLE_MAPS_API_KEY`를 본인의 Google Maps API 키로 바꿔요. (Maps JavaScript, Places, Directions, Geocoding API 사용 / HTTP 리퍼러 제한 권장)
2. 위치 권한을 쓰려면 `localhost` 또는 https로 열어요.
   ```bash
   python3 -m http.server 8000   # http://localhost:8000/?demo
   ```

## 테스트용 주소 옵션
- `?demo` — 체크인 거리·정확도 검사를 건너뛰어요.
- `?admin` — 장소별 체크인 반경·비활성화·히든 지정을 바꿀 수 있어요.

진행 기록은 브라우저 localStorage에만 저장돼요. (서버 없음)
