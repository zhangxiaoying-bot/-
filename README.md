<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>劳动最光荣，奋斗最幸福</title>
  <style>
    body {
      font-family: 'Helvetica Neue', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f8f9fa;
      color: #333;
    }
    header {
      background: url('https://images.unsplash.com/photo-1581090700227-1e8e1f3e5dce?fit=crop&w=1920&q=80') center/cover no-repeat;
      color: white;
      text-align: center;
      padding: 80px 20px;
    }
    header h1 {
      font-size: 48px;
      margin-bottom: 10px;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #dc3545;
    }
    nav a {
      color: white;
      padding: 15px 20px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      background-color: #c82333;
    }
    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .stories .card, .gallery img {
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      border-radius: 8px;
      margin: 10px;
    }
    .stories {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    .card {
      width: 300px;
      background: white;
      padding: 20px;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 10px;
    }
    form {
      display: flex;
      flex-direction: column;
    }
    form input, form textarea {
      margin-bottom: 10px;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    form button {
      padding: 10px;
      background-color: #28a745;
      color: white;
      border: none;
      border-radius: 4px;
      font-weight: bold;
    }
    footer {
      text-align: center;
      padding: 20px;
      background-color: #343a40;
      color: white;
    }
  </style>
</head>
<body>
  <header>
    <h1>劳动最光荣，奋斗最幸福</h1>
    <p>向每一位默默奉献的劳动者致敬</p>
  </header>
  <nav>
    <a href="#stories">劳动者故事</a>
    <a href="#submit">投稿留言</a>
    <a href="#gallery">劳动图集</a>
  </nav>

  <section id="stories">
    <h2>劳动者故事</h2>
    <div class="stories">
      <div class="card">
        <h3>张师傅：坚守工地三十年</h3>
        <p>他每天清晨五点准时出发，风雨无阻地奋战在城市建设第一线。</p>
      </div>
      <div class="card">
        <h3>李阿姨：城市的清晨从她开始</h3>
        <p>每天凌晨三点，李阿姨就开始清扫街道，只为城市干净整洁。</p>
      </div>
    </div>
  </section>

  <section id="submit">
    <h2>投稿留言</h2>
    <form>
      <input type="text" placeholder="您的姓名">
      <input type="text" placeholder="职业">
      <textarea rows="5" placeholder="分享您的劳动故事或留言..."></textarea>
      <button type="submit">提交</button>
    </form>
  </section>

  <section id="gallery">
    <h2>劳动者图集</h2>
    <div class="gallery">
      <img src="https://images.unsplash.com/photo-1605792657660-596af9009a1f?fit=crop&w=600&q=80" alt="工人">
      <img src="https://images.unsplash.com/photo-1593642634367-d91a135587b5?fit=crop&w=600&q=80" alt="办公室劳动者">
      <img src="https://images.unsplash.com/photo-1589820296154-dc4aa6f1baed?fit=crop&w=600&q=80" alt="医疗工作者">
      <img src="https://images.unsplash.com/photo-1568605114967-8130f3a36994?fit=crop&w=600&q=80" alt="建筑工人">
    </div>
  </section>

  <footer>
    <p>© 2025 劳动精神宣传网 | 向每一位劳动者致敬</p>
  </footer>
</body>
</html>
# -
