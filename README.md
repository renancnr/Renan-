# Renan-<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Renan Carneiro | Redes Sociais</title>
  <link rel="stylesheet" href="style.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
  <div class="container">
    <img src="renan.jpg" alt="Foto de Renan Carneiro" class="profile-pic">
    <h1>Renan Carneiro</h1>
    <p>@renan.cnr</p>

    <div class="social-links">
      <a href="https://www.instagram.com/renan.cnr?igsh=MTc1ZTBhMHpkb2JldA==" target="_blank" class="btn instagram">Instagram</a>
      <a href="https://www.facebook.com/share/18rpdVh5Wm/?mibextid=wwXIfr" target="_blank" class="btn facebook">Facebook</a>
      <a href="https://youtube.com/@cnrntj?si=6yjIJIEVFBOCoxfe" target="_blank" class="btn youtube">YouTube</a>
    </div>

    <footer>
      <p>Feito com 💻 por Renan Carneiro</p>
    </footer>
  </div>
</body>
</html>
body {
  margin: 0;
  font-family: 'Inter', sans-serif;
  background: #121212;
  color: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
}

.container {
  text-align: center;
  padding: 20px;
}

.profile-pic {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  border: 3px solid #fff;
  object-fit: cover;
  margin-bottom: 15px;
}

h1 {
  margin: 10px 0;
}

.social-links {
  display: flex;
  flex-direction: column;
  gap: 10px;
  margin-top: 20px;
}

.btn {
  text-decoration: none;
  padding: 12px 20px;
  border-radius: 8px;
  font-weight: bold;
  transition: all 0.3s ease;
  color: #fff;
}

.instagram { background: #E1306C; }
.facebook  { background: #1877F2; }
.youtube   { background: #FF0000; }

.btn:hover {
  opacity: 0.85;
}

footer {
  margin-top: 40px;
  font-size: 0.9em;
  color: #aaa;
}
