<style>
  @font-face {
  font-family: "Rugen";
  src: url("./fonts/rugen/Rugen-Expanded.eot");
  src: local("Rugen Expanded"),
    url("./fonts/rugen/Rugen-Expanded.eot?#iefix") format("embedded-opentype"),
    url("./fonts/rugen/Rugen-Expanded.woff2") format("woff2"),
    url("./fonts/rugen/Rugen-Expanded.woff") format("woff"),
    url("./fonts/rugen/Rugen-Expanded.ttf") format("truetype");
  font-weight: normal;
  font-style: normal;
  font-display: swap;
}
  .main-info {
    font-family: 'Rugen', sans-serif;
    color: darkorange;
  }
  .profile__title {
    font-size:25px;
  }
  .profile__text-greed {
    font-size: 15px;
    color: lightgreen;
  }
  .profile__text-about {
    font-size: 13px;
    color: #318CE7;
  }
  .profile__text-skills {
    font-size: 13px;
    color: #318CE7;
  }
  .profile__skills-title {
    font-size: 15px;
    color: #49B28D;
    margin-bottom: 20px;
  }
  .profile__list-skills {
    font-size: 13px;
    color: #B26D42;
    margin-bottom: 30px;
  }
  ul {
    list-style: none;
  }

  .profile__list-item {
    position: relative;
    font-size: 12px;
  }
  .profile__list-item + .profile__list-item {
    margin-top: 10px;
  }
  .profile__list-item::before {
    content: '';
    position: absolute;
    left: -20px;
    top: 50%;
    transform: translateY(-50%);
    width: 10px;
    height: 2px;
    background-color: #B26D42;
  }

  .profile__text-end {
    color: #FCE100;
    font-size: 10px;
    margin-bottom: 30px;
  }
  .profile__img {
    height: 20px;
  }

</style>

<div class="main-info profile">
  <h1 class="profile__title">Hello!</h1>

  <p class="profile__text-greed">
    My name is Denny and I am so glad to see you in my profile!
  </p>

  <p class="profile__text-about">
    I am web-developer. I like to do web-sites more attractive. And web for me is not an usual word. This is a part of my every day.
  </p>

  <h2 class="profile__skills-title">
    My skills in web:
  </h2>
    <ul class="profile__list-skills">
      <li class="profile__list-item">
      HTML5 / CSS3</li>
      <li class="profile__list-item">
      Base of JavaScript</li>
      <li class="profile__list-item">
      Git & GitHub: base</li>
      <li class="profile__list-item">
        Preprocessors: sass, scss, less
      </li>
      <li class="profile__list-item">
        Pixel Perfect
      </li>
      <li class="profile__list-item">
        Svg-sprites
      </li>
      <li class="profile__list-item">
        Gulp
      </li>
      <li class="profile__list-item">
        Webpack
      </li>
      <li class="profile__list-item">
        Bem-naming
      </li>
      <li class="profile__list-item">
        Sliders: slick.js, swiper.js
      </li>
      <li class="profile__list-item">
        Figma / Photoshop
      </li>
    </ul>
    <p class="profile__text-end">
      I know, when you every day going to your dream - you'll come to it. I am sure. Never back down and listen to you heart! My heart is belong to web-developing. 💖
    </p>
    <img class="profile__img" src="./img/your-dream-is-coming-true.png" alt="your dream is coming true">
</div>
