<template>
  <header class="primary-header">
    <img class="logo | mx-auto" src="/img/logo.svg" alt="Chef Song">
    <nav class="primary-navigation | margin-block-start-24">
      <ul class="flex-group | mx-auto">
        <li><a href="#about">About</a></li>
        <li><a href="#meals">Meals</a></li>
        <li><a href="#testimonials">Testimonials</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <section class="hero | bg-neutral-900 clr-neutral-100 text-center">
      <div class="container">
        <h1 class="fs-900 ff-accent margin-block-end-48">Homecooked meals delivered straight to your door</h1>
        <div class="flex-group mx-auto">
          <button type="button" class="button" data-type="accent">Place order</button>
          <a type="button" href="#about" class="button" data-type="outline">More info</a>
        </div>
      </div>
    </section>
    <section class="section" id="about">
      <div class="container">
        <div class="even-columns">
          <picture>
            <source srcset="/img/about.avif" type="image/avif">
            <source srcset="/img/about.webp" type="image/webp">
            <img class="shift-up box-shadow-1" src="/img/about.jpg" alt="">
          </picture>
          <div class="flow">
            <header class="section-header">
              <h2 class="fs-800 ff-accent clr-primary-500">Amazing food without the hassle</h2>
              <p class="fs-600 uppercase">we do all the work, so all you have to do is sit back and enjoy</p>
            </header>
            <p class="lead">it's ready to go</p>
            <p>Whether it's for a romantic evening with your significant other or if yor're hosting a large party and need food for a big group. we're here to help!</p>
            <p>We can cater to whatever your needs are, and ensure that our delicious food is delivered at the perfact moment, fresh, hot, and ready to eat exactly when you need it to be there.</p>
          </div>
        </div>
      </div>
    </section>
    <section class="section | bg-neutral-200 text-center">
      <div class="container">
        <header class="section-header" data-decoration="true">
          <h2 class="fs-800 ff-accent clr-primary-500">We make great food</h2>
          <p class="fs-600 uppercase">Cooking is our passion, with quality and freshness being of the utmost importance</p>
        </header>
        <div class="grid-auto-fit">
          <div>
          <h3 class="fs-500 fw-bold clr-neutral-900 uppercase">This is a subtitle</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam egestas egestas dignissim. Quisque
            pretium nisi a rhoncus posuere.</p>
          </div>
          <div>
            <h3 class="fs-500 fw-bold clr-neutral-900 uppercase">This is a subtitle</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam egestas egestas dignissim. Quisque
              pretium nisi a rhoncus posuere.</p>
          </div>
          <div>
            <h3 class="fs-500 fw-bold clr-neutral-900 uppercase">This is a subtitle</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam egestas egestas dignissim. Quisque
              pretium nisi a rhoncus posuere.</p>
          </div>
          <div>
            <h3 class="fs-500 fw-bold clr-neutral-900 uppercase">This is a subtitle</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam egestas egestas dignissim. Quisque
              pretium nisi a rhoncus posuere.</p>
          </div>
        </div>
      </div>
    </section>


    <section class="section clr-neutral-100 bg-neutral-900" id="meals">
      <div class="container" data-type="wide">
        <header class="section-header | text-center" data-decoration="true">
          <h2 class="fs-800">This is a nice big headline</h2>
          <p class="fs-600 uppercase">This is a subhead which mentions som interesting things</p>
        </header>

        <div class="even-columns">
          <!-- column 1 -->
            <figure class="interactive-figure">
              <picture>
                <source srcset="/img/meal-01.avif" type="image/avif">
                <source srcset="/img/meal-01.webp" type="image/webp">
                <img src="/img/meal-01.jpg" loading="lazy"
                  alt="A nicely presented plate with a cooked peice of salmon on top of a bed of vegetables, with more vegetables on top of it">
              </picture>
              <figcaption class="padding-32">
                <h3 class="fs-500 fw-bold uppercase">About this meal</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam egestas egestas dignissim.</p>
              </figcaption>
            </figure>

        <!-- column 2 -->
          <figure class="interactive-figure">
            <picture>
              <source srcset="/img/meal-02.avif" type="image/avif">
              <source srcset="/img/meal-02.webp" type="image/webp">
              <img src="/img/meal-02.jpg" loading="lazy"
                alt="Several steak tacos on a table, along with several limes">
            </picture>
            <figcaption class="padding-32">
              <h3 class="fs-500 fw-bold uppercase">About this meal</h3>
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam egestas egestas dignissim.</p>
            </figcaption>
          </figure>

        <!-- column 3 -->
          <figure class="interactive-figure">
            <picture>
              <source srcset="/img/meal-03.avif" type="image/avif">
              <source srcset="/img/meal-03.webp" type="image/webp">
              <img src="/img/meal-03.jpg" loading="lazy" alt="Clams being tossed in a pan">
            </picture>
            <figcaption class="padding-32">
              <h3 class="fs-500 fw-bold uppercase">About this meal</h3>
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam egestas egestas dignissim.</p>
            </figcaption>
          </figure>
        </div>
        </div>
    </section>


    <section class="testimonials section" id="testimonials">
      <div class="container" data-type="wide">
        <header class="section-header">
          <h2 class="fs-800 clr-primary-500 ff-accent">What our clients are saying about us</h2>
        </header>
        <div class="even-columns">
          <div class="card | box-shadow-1 text-center" data-type="testimonial">
            <picture>
              <source srcset="/img/testimonial-01.avif" type="image/avif">
              <source srcset="/img/testimonial-01.webp" type="image/webp">
              <img src="/img/testimonial-01.jpg" alt="A man standing outside, smiling">
            </picture>
            <div class="card__body">
              <p>Johon Wellington and his team make the most amazing food. Every single time I've ordered. I've been blown-away by the quality. You can tell they only use fresh ingredients and put a lot of love into every single meal they make! You really can't ask for anything more. It's always fantastic</p>
            </div>
            <div class="testimonial__footer | padding-16 bg-neutral-200">
              <p class="fs-500 clr-accent-500">John Deer</p>
              <p>Manager at Food</p>
            </div>
          </div>
          <div class="card | box-shadow-1 text-center" data-type="testimonial">
            <picture>
              <source srcset="/img/testimonial-02.avif" type="image/avif">
              <source srcset="/img/testimonial-02.webp" type="image/webp">
              <img src="/img/testimonial-02.jpg" alt="A man standing outside, smiling">
            </picture>
            <div class="card__body">
              <p>I'm so happy that I found John Wellington! The food is on par with some of the best restaurants I've ever eaten at, but from the comfort of my own home. Every single time I order. it's mouthwateringly delicious.</p>
            </div>
            <div class="testimonial__footer | padding-16 bg-neutral-200">
              <p class="fs-500 clr-accent-500">Marie Condo</p>
              <p>Foodle</p>
            </div>
          </div>
          <div class="card | box-shadow-1 text-center" data-type="testimonial">
            <picture>
              <source srcset="/img/testimonial-03.avif" type="image/avif">
              <source srcset="/img/testimonial-03.webp" type="image/webp">
              <img src="/img/testimonial-03.jpg" alt="A man standing outside, smiling">
            </picture>
            <div class="card__body">
              <p>From simple meals to some of the most extravagant thing 'Ive ever eaten. John and his team always deliver. Every time I order something new. I just can't wait for it to be deliverd and I know how mouth-wateringly declicious it's going to be. If you like good food, you have to give it a try!</p>
            </div>
            <div class="testimonial__footer | padding-16 bg-neutral-200">
              <p class="fs-500 clr-accent-500">Sam Reinhert</p>
              <p>Good food enthusiast</p>
            </div>
          </div>
        </div>

      </div>
    </section>
  </main>
  <footer class="primary-footer section | bg-neutral-900 clr-neutral-100 text-center flow">
    <div class="container">
      <p class="fw-bold">Homecooked mealsdelivered straight to your door</p>
      <p>©2022 Persronal Chef Services</p>
      <p>555 Boulevard Anywhere, Montreal, Quebec, J1S 1S9 | 123-555-1234</p>
    </div>
  </footer>
</template>
