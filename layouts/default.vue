<template>
  <section>
        <nav
        class="navbar is-fixed-top is-transparent"
        >
        <div class="navbar-brand">
          <a
          class="navbar-item"
          v-scroll-to="'#hero'"
          >
          <img
          src="/Tip-Top_logo.png"
          alt="Tip-Top"
          id="logo"
          >
        </a>
      </div>
      <div class="navbar-item">
        <a
        v-scroll-to="'#text2'"
        class="navbar-item"
        >
        FAQ
      </a>
    </div>
    <div class="navbar-item">
      <a
      class="navbar-item"
      href="/Tip-Top_one-pager.pdf"
      target="_blank"
      >
      WHITEPAPER
    </a>
  </div>
  <div class="navbar-item">
    <a
    class="navbar-item"
    href="https://www.twitter.com/@tiptopNFT"
    >
    <img
    id="twitterim"
    src="/twitter_icon.png"
    alt="Twitter.com"
    >
    Twitter
  </a>
</div>
<div class="navbar-burger">
</div>
</nav>
<nuxt />
</section>
</template>
