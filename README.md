<!DOCTYPE html>
<html lang="az">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Veb Səhifənin Yaradılması</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f7f7f7;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #0077cc;
      color: white;
      padding: 20px;
      text-align: center;
    }
    section {
      padding: 20px;
    }
    img {
      width: 100%;
      max-width: 500px;
      display: block;
      margin: 20px auto;
    }
    button {
      background-color: #0077cc;
      color: white;
      padding: 10px 20px;
      border: none;
      cursor: pointer;
    }
    form {
      margin-top: 20px;
    }
    input, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Veb Səhifənin Yaradılması və Funksiyaları</h1>
  </header>

  <section>
    <h2>Veb Səhifə nədir?</h2>
    <p>Veb səhifə internet üzərindən baxıla bilən sənəddir. HTML, CSS və JavaScript kimi texnologiyalarla yaradılır.</p>
    
    <h2>Əsas funksiyalar</h2>
    <ul>
      <li>Məlumat təqdim etmək</li>
      <li>İstifadəçi ilə əlaqə qurmaq (formalar vasitəsilə)</li>
      <li>Vizual dizayn və interaktiv elementlər</li>
    </ul>

    <img src="https://via.placeholder.com/500x300.png?text=Veb+S%C9%99hif%C9%99+N%C3%BCmun%C9%99si" alt="Veb səhifə nümunəsi">

    <button onclick="alert('Veb səhifəyə xoş gəlmisiniz!')">Xoş gəlmisiniz</button>

    <h2>Bizimlə əlaqə</h2>
    <form>
      <label for="name">Adınız:</label>
      <input type="text" id="name" name="name" placeholder="Adınızı daxil edin">

      <label for="message">Mesajınız:</label>
      <textarea id="message" name="message" rows="4" placeholder="Mesajınızı yazın"></textarea>

      <button type="submit">Göndər</button>
    </form>
  </section>

</body>
</html>
