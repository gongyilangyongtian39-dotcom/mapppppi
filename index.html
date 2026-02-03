<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>世界遺産マップ</title>

  <!-- Leaflet -->
  <link
    rel="stylesheet"
    href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css"
  />

  <style>
    body {
      margin: 0;
      font-family: system-ui, sans-serif;
      background: #f2f2f2;
    }

    header {
      padding: 12px;
      background: #222;
      color: white;
      text-align: center;
    }

    #search {
      width: 90%;
      max-width: 400px;
      padding: 8px 12px;
      margin-top: 10px;
      border-radius: 8px;
      border: none;
      font-size: 16px;
    }

    #map {
      height: calc(100vh - 110px);
    }

    .popup-title {
      font-weight: bold;
      color: #c62828;
    }

    .popup-desc {
      font-size: 14px;
      margin-top: 4px;
    }
  </style>
</head>
<body>

<header>
  <h2>🌍 世界遺産マップ</h2>
  <input id="search" type="text" placeholder="世界遺産を検索（例：富士山）">
</header>

<div id="map"></div>

<script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"></script>
<script>
  // 世界遺産データ（サンプル）
  const heritages = [
    {
      name: "富士山",
      desc: "日本を代表する霊峰。",
      lat: 35.3606,
      lng: 138.7274
    },
    {
      name: "タージ・マハル",
      desc: "インドの白い大理石の霊廟。",
      lat: 27.1751,
      lng: 78.0421
    },
    {
      name: "マチュ・ピチュ",
      desc: "インカ帝国の空中都市。",
      lat: -13.1631,
      lng: -72.5450
    },
    {
      name: "コロッセオ",
      desc: "古代ローマの円形闘技場。",
      lat: 41.8902,
      lng: 12.4922
    }
  ];

  const map = L.map('map').setView([20, 0], 2);

  L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
    attribution: '© OpenStreetMap contributors'
  }).addTo(map);

  const markers = [];

  const redIcon = L.icon({
    iconUrl: 'https://raw.githubusercontent.com/pointhi/leaflet-color-markers/master/img/marker-icon-red.png',
    shadowUrl: 'https://unpkg.com/leaflet@1.9.4/dist/images/marker-shadow.png',
    iconSize: [25, 41],
    iconAnchor: [12, 41]
  });

  function showMarkers(list) {
    markers.forEach(m => map.removeLayer(m));
    markers.length = 0;

    list.forEach(h => {
      const marker = L.marker([h.lat, h.lng], { icon: redIcon })
        .addTo(map)
        .bindPopup(`
          <div class="popup-title">${h.name}</div>
          <div class="popup-desc">${h.desc}</div>
        `);

      markers.push(marker);
    });
  }

  showMarkers(heritages);

  // 検索機能
  document.getElementById('search').addEventL
