<template>
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
</template>
