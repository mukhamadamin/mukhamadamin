<!-- Приветствие -->
<h1 align="center">Привет, я Mukhamadamin 👋</h1>
<p align="center">
  Flutter-разработчик из Узбекистана 🇺🇿 <br>
  Люблю создавать красивые и удобные мобильные приложения
</p>

<!-- Бейджи -->
<p align="center">
  <img src="https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white"/>
  <img src="https://img.shields.io/badge/Dart-%230175C2.svg?style=for-the-badge&logo=Dart&logoColor=white"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black"/>
  <img src="https://img.shields.io/badge/Android-%2300B0FF.svg?style=for-the-badge&logo=Android&logoColor=white"/>
  <img src="https://img.shields.io/badge/iOS-%2300A1D4.svg?style=for-the-badge&logo=apple&logoColor=white"/>
  <img src="https://img.shields.io/badge/VS_Code-%23007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-%23F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/HTML-%23E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS-%231572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-%2300D8FF?style=for-the-badge&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/GraphQL-%23E10098?style=for-the-badge&logo=graphql&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQLite-%2307405E?style=for-the-badge&logo=sqlite&logoColor=white"/>
  <img src="https://img.shields.io/badge/Swift-%23F05138?style=for-the-badge&logo=swift&logoColor=white"/>
</p>

<!-- О себе -->
## 🚀 Немного обо мне

- 💼 Flutter-разработчик с опытом коммерческой разработки
- 👨‍💻 Люблю писать чистый и поддерживаемый код
- 🎯 Постоянно учусь и пробую новые технологии

<!-- Технологии -->
## 🛠️ Мой стек

- **Flutter, Dart**
- Firebase (Firestore, Auth, Storage, Crashlytics)
- REST API, GraphQL
- Git & GitHub
- Provider, BLoC, Riverpod
- MVC, MVVM, Clean architecture, FSD
- Figma, Zeplin

<!-- Статистика -->
## 📊 GitHub статистика

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=mukhamadamin&show_icons=true&theme=tokyonight" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mukhamadamin&layout=compact&theme=tokyonight" height="150"/>
</p>

<!-- Контакты -->
## 📫 Контакты

- Telegram: [@yourtelegram](https://t.me/maheyev)
- Email: muhammadaminyahyoyev@example.com
- LinkedIn: [linkedin.com/in/yourprofile](https://www.linkedin.com/in/muhammadamin-yahyoyev-21a802258/)

<!-- Карта с местоположением -->
<h3 align="center">Мое местоположение</h3>
<div id="map" style="height: 400px;"></div>
<script>
  function initMap() {
    var map = new google.maps.Map(document.getElementById("map"), {
      center: { lat: 41.2995, lng: 69.2401 }, // Координаты Узбекистана
      zoom: 8,
    });
    var marker = new google.maps.Marker({
      position: { lat: 41.2995, lng: 69.2401 },
      map: map,
      title: "Мое местоположение!",
    });
  }
</script>
<script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap" async defer></script>

<!-- Модальные окна с проектами -->
<h3 align="center">Мои проекты</h3>
<button onclick="showProjectDetails()">Посмотреть проекты</button>

<script src="https://cdn.jsdelivr.net/npm/sweetalert2@11"></script>
<script>
  function showProjectDetails() {
    Swal.fire({
      title: 'Мой последний проект',
      text: 'Описание проекта...',
      imageUrl: 'project-image-url.jpg',
      imageWidth: 400,
      imageHeight: 200,
      imageAlt: 'Project Image',
    });
  }
</script>

<!-- Слайдер с отзывами -->
<h3 align="center">Отзывы</h3>
<div class="swiper-container" style="width: 80%; margin: 0 auto;">
  <div class="swiper-wrapper">
    <div class="swiper-slide">"Отличная работа! Очень профессионально!"</div>
    <div class="swiper-slide">"Mukhamadamin - лучший разработчик, с которым я работал!"</div>
    <div class="swiper-slide">"Всегда в срок, всегда качественно!"</div>
  </div>
  <div class="swiper-pagination"></div>
</div>
<script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>
<script>
  var swiper = new Swiper('.swiper-container', {
    slidesPerView: 1,
    spaceBetween: 10,
    pagination: {
      el: '.swiper-pagination',
      clickable: true,
    },
  });
</script>

<!-- Цитаты -->
<h3 align="center">Мои любимые цитаты</h3>
<div style="text-align: center; margin-top: 40px;">
  <blockquote>
    <p>"Программирование - это не просто работа. Это искусство."</p>
    <footer>- Автор</footer>
  </blockquote>
  <blockquote>
    <p>"Каждый баг — это возможность учиться."</p>
    <footer>- Автор</footer>
  </blockquote>
</div>

<!-- Интерактивная кнопка для социальных сетей -->
<p align="center">
  <a href="https://twitter.com/yourusername" target="_blank">
    <button style="padding: 10px 20px; border-radius: 5px; background-color: #1DA1F2; color: white;">Мой Twitter</button>
  </a>
  <a href="https://www.instagram.com/yourusername" target="_blank">
    <button style="padding: 10px 20px; border-radius: 5px; background-color: #C13584; color: white;">Мой Instagram</button>
  </a>
</p>

<!-- Кнопка с анимацией -->
<p align="center">
  <button class="animated-button">Связаться со мной</button>
</p>
<style>
  .animated-button {
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    background-color: #0a66c2;
    color: white;
    font-size: 16px;
    cursor: pointer;
    transition: transform 0.3s ease;
  }
  .animated-button:hover {
    transform: scale(1.1);
  }
</style>

<!-- Анимации при прокрутке -->
<h3 align="center">Мои проекты</h3>
<div data-aos="fade-up">
  <p>Описание проекта...</p>
</div>
<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>
  AOS.init();
</script>

<!-- Чат-бот -->
<h3 align="center">Задать вопрос</h3>
<p align="center">
  <button onclick="window.location.href='mailto:muhammadaminyahyoyev@example.com'">Написать мне</button>
</p>

<!-- Красивая подпись -->
## ✨ Спасибо за внимание! 
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:26c6da,100:1976d2&height=100&section=footer&text=Будь%20в%20курсе%20новых%20проектов%20и%20разработок%20с%20Mukhamadamin&fontSize=25&fontColor=fff&animation=fadeIn"/>
</p>

<!-- Интерактивная кнопка -->
<p align="center">
  <a href="https://github.com/mukhamadamin" target="_blank">
    <button style="padding: 10px 20px; border: none; border-radius: 5px; background-color: #0a66c2; color: white; font-size: 16px; cursor: pointer;">
      Подписаться на GitHub
    </button>
  </a>
</p>

<script>
  // Initialize Map
  function initMap() {
    var map = new google.maps.Map(document.getElementById("map"), {
      center: { lat: 41.2995, lng: 69.2401 },
      zoom: 8,
    });
    var marker = new google.maps.Marker({
      position: { lat: 41.2995, lng: 69.2401 },
      map: map,
      title: "Мое местоположение!",
    });
  }
</script>
<script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap" async defer></script>
