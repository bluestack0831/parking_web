# 주차 위치를 지도에 표시하기 위한 웹
https://pswon5894.github.io/parking_web/
## 저작자표시 - OpenStreetMap 데이터를 자유롭게 복사, 배포, 전송 및 적용하려면 OpenStreetMap 기여자를 명시해야 합니다.

// 예시 마커 (주차 위치)
// const parkingMarker = L.marker([37.5665, 126.9780])
//     .addTo(map)
//     .bindPopup('현재 주차 위치');

// 서버에서 위치 받아오는 예시
/*
fetch('https://your-server.com/locations')
  .then(res => res.json())
  .then(data => {
    data.forEach(car => {
      L.marker([car.lat, car.lng])
        .addTo(map)
        .bindPopup(`차량 ID: ${car.carId}`);
    });
  });
*/


// 반드시 “© OpenStreetMap contributors”를 표시해야 한다, 라이센스
