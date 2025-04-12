<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Священное Писание</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(to bottom, #f9f9f9, #dcdcdc);
      background-image: url('https://upload.wikimedia.org/wikipedia/commons/thumb/d/d2/Christian_cross.svg/1200px-Christian_cross.svg.png');
      background-repeat: no-repeat;
      background-position: center top;
      background-size: 100px;
      padding-top: 140px;
      color: #333;
      text-align: center;
    }

    h1 {
      font-size: 32px;
      margin-bottom: 30px;
      color: #222;
    }

    .main-button {
      background-color: #4A90E2;
      color: white;
      padding: 15px 30px;
      margin: 10px;
      font-size: 18px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      transition: background-color 0.3s ease;
    }

    .main-button:hover {
      background-color: #357ABD;
    }

    .dropdown {
      display: none;
      margin-top: 10px;
    }

    .dropdown a {
      display: block;
      background-color: #ffffff;
      color: #333;
      text-decoration: none;
      padding: 12px;
      margin: 6px auto;
      width: 240px;
      border-radius: 6px;
      border: 1px solid #ccc;
      transition: all 0.3s;
    }

    .dropdown a:hover {
      background-color: #f1f1f1;
      transform: scale(1.02);
    }

    footer {
      margin-top: 50px;
      font-size: 14px;
      color: #777;
    }
  </style>
</head>
<body>

  <h1>Священное Писание</h1>

  <!-- Тора -->
  <button class="main-button" onclick="toggleDropdown('torahDropdown')">Тора</button>
  <div id="torahDropdown" class="dropdown">
    <a href="https://ebible.org/pdf/russyn/russyn_GEN.pdf" target="_blank">Бытие</a>
    <a href="https://ebible.org/pdf/russyn/russyn_EXO.pdf" target="_blank">Исход</a>
    <a href="https://ebible.org/pdf/russyn/russyn_LEV.pdf" target="_blank">Левит</a>
    <a href="https://ebible.org/pdf/russyn/russyn_NUM.pdf" target="_blank">Числа</a>
    <a href="https://ebible.org/pdf/russyn/russyn_DEU.pdf" target="_blank">Второзаконие</a>
  </div>

  <!-- Евангелие -->
  <button class="main-button" onclick="toggleDropdown('gospelDropdown')">Евангелие</button>
  <div id="gospelDropdown" class="dropdown">
    <a href="https://ebible.org/pdf/russyn/russyn_MAT.pdf" target="_blank">Матфея</a>
    <a href="https://ebible.org/pdf/russyn/russyn_MRK.pdf" target="_blank">Марка</a>
    <a href="https://ebible.org/pdf/russyn/russyn_LUK.pdf" target="_blank">Луки</a>
    <a href="https://ebible.org/pdf/russyn/russyn_JHN.pdf" target="_blank">Иоанна</a>
  </div>

  <footer>
    <p>© 2025 | Роланд Логуа | "Слово Твоё — светильник ноге моей" (Пс. 118:105)</p>
  </footer>

  <script>
    function toggleDropdown(id) {
      const dropdown = document.getElementById(id);
      dropdown.style.display = dropdown.style.display === "block" ? "none" : "block";
    }
  </script>

</body>
</html>
