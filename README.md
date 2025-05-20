<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Kamu</title>
  <style>
    body {
      background: linear-gradient(#ffe6f0, #fff);
      font-family: 'Segoe UI', sans-serif;
      text-align: center;
      padding: 50px;
    }

    h1 {
      color: #d10068;
      font-size: 3em;
    }

    p {
      font-size: 1.3em;
      color: #660033;
      max-width: 700px;
      margin: auto;
      line-height: 1.6;
    }

    img {
      margin-top: 30px;
      max-width: 300px;
      border-radius: 20px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }

    button {
      margin-top: 40px;
      background-color: #ff66a3;
      color: white;
      padding: 15px 30px;
      font-size: 18px;
      border: none;
      border-radius: 12px;
      cursor: pointer;
    }

    button:hover {
      background-color: #cc0052;
    }

    .hidden-message {
      display: none;
      margin-top: 30px;
      font-size: 1.2em;
      color: #b3005f;
    }
  </style>
</head>
<body>

  <h1>Hai!!</h1>
  <p>
    Ga mudah emang tapi aku yakin kamu bisa lewatinnya karena bagaimanapun cuma kamu yang bisa jalaninnya
  </p>
  <p>
  Jangan lupa buat selalu ucapin terimakasih ke dirimu sendiri dari setiap pencapaian kecil dihidupmu
  </p>

  <p>
    Jangan minder dengan apapun pencapaian orang lain yaa, semua punya rantai pencapaiannya masing-masing. 
    Semangat dan sehat selalu kamu 
  </p>

  <button onclick="tampilkanPesan()">pencet aja</button>

  <div class="hidden-message" id="pesanRahasia">
    Selalu Jadi perempuan hebat yang aku kenal itu yaa.. 
    yang senyumnya selalu ditunggu oleh dunia, juga yang selalu jadi alasan orang lain untuk bisa tersenyum juga 
  </div>

  <script>
    function tampilkanPesan() {
      document.getElementById("pesanRahasia").style.display = "block";
    }
  </script>

</body>
</html>
