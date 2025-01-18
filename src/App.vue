<script setup>
import rec_12 from './assets/Social_icons/Rectangle 12.png';
import rec_14 from './assets/Social_icons/Rectangle 14.png';
import img_5 from './assets/Social_icons/image 5.png';
import img_4 from './assets/Social_icons/image 4.png';
import location from './assets/Social_icons/location.png';
import phone_1 from './assets/Social_icons/phone-1.png';
import phone from './assets/Social_icons/phone.png';
import dough from './assets/dough-3082589_1920 1.png';
import pizza1 from './assets/pizza1 1.png';
import pizza2 from './assets/Food_items/pizza2.png';
import pizza5 from './assets/Food_items/pizza5.png';
import shake1 from './assets/Food_items/shake1.png';
import bread from './assets/Food_items/bread.png';
import bread2 from './assets/Food_items/bread2.png';
import Untitled from './assets/Food_items/Untitled.png'; 
import group from './assets/Group.png';
import envelope from './assets/Social_icons/envelope.png';
</script>

<template>
  <header>
    <div class="navbar">
      <div class="logo">
        <h2>Pizza Restaurant</h2>
      </div>
      <div class="navigation">
        <li><a href="#">ABOUT US</a></li>
        <li><a href="#">MENU</a></li>
        <li><a href="#">BLOGS</a></li>
        <li><a href="#">TESTIMONY</a></li>
        <li><a href="#">FIND US</a></li>
        <li><a href="#">OUR TEAM</a></li>
      </div>
      <div class="social-navigation">
        <div class="icons img1">
          <img :src='rec_12' alt="no-img" srcset="" />
        </div>
        <div class="icons img2">
          <img :src="img_5" alt="no-img" srcset="" />
        </div>
        <div class="icons img3">
          <img :src="img_4" alt="no-img" srcset="" />
        </div>
      </div>
    </div>
  </header>
  <main>
    <div class="information">
      <img :src="pizza1" alt="" />
      <div class="heading">
        <div class="heading-h1">
          <h1>Craving for a chessy pizza?</h1>
          <img :src="rec_14" alt="" />
          <p class="heading-p">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus
            ac placerat dui. Vestibulum ut felis et lorem porta congue vitae
            nec turpis. Aliquam quis leo at nunc tempor faucibus et ac massa.
          </p>
        </div>
      </div>
    </div>
    <section class="about-us">
      <div class="commen">
        <h2 class="about-heading">ABOUT US</h2>
        <img :src="rec_14" alt="" />
      </div>
      <div class="about-container">
        <div class="about-text">
          <img :src="rec_14" alt="" />
          <p>
            Lorem Ipsum is simply dummy text of the printing and typesetting
            industry. Lorem Ipsum has been the industry's standard dummy text
            ever since the 1500s, when an unknown printer took a galley of
            type and scrambled it to make a type specimen book. It has
            survived not only five centuries, but also the leap into
            electronic typesetting, remaining essentially unchanged.
          </p>
        </div>
        <div class="about-img">
          <img :src="dough" alt="" />
        </div>
      </div>
    </section>
    <section class="menu">
      <div class="commen">
        <h2 class="menu-heading">Menu</h2>
        <img :src="rec_14" alt="" />
      </div>
      <p>
        Explore the wide range of pizza baked in fresh dough and vegetables.
        Our pizza will tempt all your excitement and senses. Made with a
        delicate balance of everything cheesy and spicy, you will get to
        savour the best pizza in town.
      </p>
      <div class="menu-container">
        <div class="menu-item">
          <div class="menu-img">
            <img :src="bread" height="200px" width="274px" alt="" />
          </div>
          <div class="menu-text">
            <h2 class="menu-item-name">LOREM IPSUM</h2>
            <p class="menu-item-desc">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              Phasellus ac placerat dui.
            </p>
          </div>
        </div>
        <div class="menu-item">
          <div class="menu-img">
            <img :src="bread2" height="200px" width="274px" alt="" />
          </div>
          <div class="menu-text">
            <h2 class="menu-item-name">LOREM IPSUM</h2>
            <p class="menu-item-desc">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              Phasellus ac placerat dui.
            </p>
          </div>
        </div>
        <div class="menu-item">
          <div class="menu-img">
            <img :src="pizza2" height="200px" width="274px" alt="" />
          </div>
          <div class="menu-text">
            <h2 class="menu-item-name">LOREM IPSUM</h2>
            <p class="menu-item-desc">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              Phasellus ac placerat dui.
            </p>
          </div>
        </div>
        <div class="menu-item">
          <div class="menu-img">
            <img :src="pizza5" height="200px" width="274px" alt="" />
          </div>
          <div class="menu-text">
            <h2 class="menu-item-name">LOREM IPSUM</h2>
            <p class="menu-item-desc">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              Phasellus ac placerat dui.
            </p>
          </div>
        </div>
        <div class="menu-item">
          <div class="menu-img">
            <img :src="shake1" height="200px" width="274px" alt="" />
          </div>
          <div class="menu-text">
            <h2 class="menu-item-name">LOREM IPSUM</h2>
            <p class="menu-item-desc">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              Phasellus ac placerat dui.
            </p>
          </div>
        </div>
        <div class="menu-item">
          <div class="menu-img">
            <img :src="Untitled" height="200px" width="274px" alt="" />
          </div>
          <div class="menu-text">
            <h2 class="menu-item-name">LOREM IPSUM</h2>
            <p class="menu-item-desc">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              Phasellus ac placerat dui.
            </p>
          </div>
        </div>
      </div>
    </section>
    <section class="carousel-sec">
      <div class="commen">
        <h2 class="carousel-heading">CAROUSEL</h2>
        <img :src="rec_14" alt="" />
      </div>

      <div class="carousel-container">
        <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
          <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active"
              aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1"
              aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2"
              aria-label="Slide 3"></button>
            <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="3"
              aria-label="Slide 4"></button>
            <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="4"
              aria-label="Slide 5"></button>
          </div>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img :src="pizza2" class="d-block w-100" alt="..." />
            </div>
            <div class="carousel-item">
              <img :src="pizza2" class="d-block w-100" alt="..." />
            </div>
            <div class="carousel-item">
              <img :src="pizza2" class="d-block w-100" alt="..." />
            </div>
            <div class="carousel-item">
              <img :src="pizza2" class="d-block w-100" alt="..." />
            </div>
            <div class="carousel-item">
              <img :src="pizza2" class="d-block w-100" alt="..." />
            </div>
          </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators"
            data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators"
            data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
      </div>
    </section>
    <section class="gallary">
      <div class="commen">
        <h2 class="gallary-heading">GALLARY</h2>
        <img :src="rec_14" alt="" />
      </div>
      <div class="gallary-box">
        <div class="gallary-container">
          <img class="gallary-img-1" :src="pizza2" alt="" />

          <img class="gallary-img-2" :src="bread" alt="" />

          <img class="gallary-img-3" :src="bread2" alt="" />

          <img class="gallary-img-4" :src="pizza5" alt="" />

          <img class="gallary-img-5" :src="shake1" alt="" />

          <img class="gallary-img-6" :src="Untitled" alt="" />
        </div>
      </div>
    </section>

    <section class="findus">
      <div class="commen">
        <h2 class="findus-heading">FIND US</h2>
        <img :src="rec_14" alt="" />
      </div>
      <div class="findus-container">
        <div class="info-1">
          <p>
            Lorem Ipsum is simply dummy text of the printing and typesetting
            industry. Lorem Ipsum has been the industry's standard dummy text
            e.
          </p>
          <div class="location">
            <div class="loc-img">
              <img :src="location" alt="" />
            </div>
            <div class="loc-info">
              <p>Location XYZ, XYZ Colony, Delhi</p>
            </div>
          </div>
          <div class="phone">
            <div class="phone-img">
              <img :src="phone_1" alt="" />
            </div>
            <div class="phone-info">
              <p>123-456-789</p>
              <p>987-654-321</p>
            </div>
          </div>
        </div>
        <div class="info-2">
          <div class="google-map">
            <iframe
              src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d1348444.4696904423!2d69.78216855529837!3d23.0535601498842!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sen!2sin!4v1688462505257!5m2!1sen!2sin"
              width="400" height="300" style="border: 0" allowfullscreen="" loading="lazy"
              referrerpolicy="no-referrer-when-downgrade"></iframe>
          </div>
        </div>
      </div>
    </section>
    <footer class="footer-sec">
      <div class="foot-logo">
        <img :src="group" alt="" />
      </div>
      <div class="foot-info">
        <div class="foot-info-1">
          <div class="info-1-img">
            <img :src="envelope" alt="" />
          </div>
          <div class="info-1-desc">
            <p>mailid@gmail.com</p>
          </div>
        </div>
        <div class="foot-info-2">
          <div class="info-2-img">
            <img :src="phone" alt="" />
          </div>
          <div class="info-2-desc">
            <p>123-456-789</p>
            <p>987-654-321</p>
          </div>
        </div>
      </div>
    </footer>
  </main>
</template>