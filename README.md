# Swiper.js

Swiper is the most modern free mobile touch slider with hardware accelerated transitions and amazing native behavior.

## Installation

Use UNPKG - [CSS file](https://unpkg.com/swiper@7/swiper-bundle.min.css)  ,[JavaScript file](https://unpkg.com/swiper@7/swiper-bundle.min.js)
or
CDN - [CSS file](https://cdnjs.cloudflare.com/ajax/libs/Swiper/7.4.1/swiper-bundle.css) , [JavaScript file](https://cdnjs.cloudflare.com/ajax/libs/Swiper/7.4.1/swiper-bundle.min.js).

```css
<link rel="stylesheet" href="https://unpkg.com/swiper@7/swiper-bundle.min.css"/>
```

```javascript
<script src="https://unpkg.com/swiper@7/swiper-bundle.min.js"></script>
```

## Usage

```html
<!-- Slider main container -->
<div class="swiper">
  <!-- Additional required wrapper -->
  <div class="swiper-wrapper">
    <!-- Slides -->
    <div class="swiper-slide">Slide 1</div>
    <div class="swiper-slide">Slide 2</div>
    <div class="swiper-slide">Slide 3</div>
    ...
  </div>
  <!-- If we need pagination -->
  <div class="swiper-pagination"></div>

  <!-- If we need navigation buttons -->
  <div class="swiper-button-prev"></div>
  <div class="swiper-button-next"></div>

  <!-- If we need scrollbar -->
  <div class="swiper-scrollbar"></div>
</div>
```
```css
.swiper {
  width: 600px;
  height: 300px;
}
```

```javascript
const swiper = new Swiper('.swiper', {
  // Optional parameters
  direction: 'vertical',
  loop: true,

  // If we need pagination
  pagination: {
    el: '.swiper-pagination',
  },

  // Navigation arrows
  navigation: {
    nextEl: '.swiper-button-next',
    prevEl: '.swiper-button-prev',
  },

  // And if we need scrollbar
  scrollbar: {
    el: '.swiper-scrollbar',
  },
});
```

## Subscribe
Please subscribe [CodeWithNiranjan](https://youtube.com/channel/UCzfQyi4_E-lS9ps3fVb0jlA)

<h1>Thank You</h1>
