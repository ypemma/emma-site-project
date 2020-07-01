<template>
  <div id="contact-page" class="page-wrapper contact-page content-page">
    <site-hero
      title="How to find me"
      image="/uploads/contact-hero.jpg"
    ></site-hero>
    <main-section theme="sidebar-right">
      <template v-slot:default>
        <div class="tile is-ancestor">
          <div class="tile is-parent">
            <article class="tile is-child box">
              <p class="title">
                Hello!
              </p>
              <p class="subtitle">
                Here are all the places you can find me online!
              </p>
              
              <br />
              <div class="content">
                <p>
                  <strong>
                   Emma is a writer, photographer and all around nice person.
                  </strong>
                </p>
                <p>
                 Use these links to find her online. Don't be scared to reach out anytime!
                </p>
              </div>
            </article>
          </div>
          <div class = "tile is-parent is-8">
            <article class = "tile is-child box">
              <h4>
                Twitter
              </h4>
                <p>
                  @YourPalEmma
                </p>
              <br><br>
              <h4>
                Email
              </h4>
              <p>
                em@emmawrites.co
              </p>
            </article>
          </div>
        </div>
      </template>
      <template v-slot:sidebar>
        <h3 class="subtitle is-4">
          Latest Posts
        </h3>
        <!-- Latest Posts -->
        <posts-grid :per-row="1" :number="2" />
      </template>
    </main-section>
  </div>
</template>
