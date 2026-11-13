<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Form Nama</title>
</head>
<body>
  <h2>Form Nama</h2>

  <label>Nama depan:</label><br>
  <input type="text" id="depan"><br><br>

  <label>Nama belakang:</label><br>
  <input type="text" id="belakang"><br><br>

  <button onclick="tampilkan()">Kirim</button>

  <p id="hasil"></p>

  <script>
    function tampilkan() {
      const depan = document.getElementById("depan").value;
      const belakang = document.getElementById("belakang").value;
      document.getElementById("hasil").innerText =
        "Halo, " + depan + " " + belakang;
    }
  </script>
</body>
</html>
