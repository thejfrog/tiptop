<template>
  <section id="header">
    <nav id= "level1" class="level">
      <div id="text1" class="level-left">
        Tip-Top is a web3-native social-media-based NFT creation
        platform
      </div>
    </nav>
    <nav id="level2" class="level">
      <div id="text2" class="level-left">
        FAQ
      </div>
    </nav>
    <div id='FAQ' class="level">
      <div class="level-item">
        <div id="card1" class="card">
          <div class="card-image">
            <div class="image">
              <b-carousel
              :arrow=false
              :pause-info=false
              :indicator=false>
              <b-carousel-item
              v-for="(carousel, i) in carousels"
              :key="i"
              >
              <img
              :src="carousel.image"
              >
            </b-carousel-item>
          </b-carousel>
        </div>
      </div>
      <header class="card-header-title">
        <p class="card-header-title">
          How does it work?
        </p>
      </header>
      <div id="text3" class="content">
        <br>
        Creators mint NFTs through the Tip-Top smart contract.<br><br>The Tip-Top smart contract hard-caps NFT supply based<br>
        on social media post engagement, creating a guarantee<br>on the scarcity of NFTs minted through the platform.<br><br>
        A guaranteed supply cap benefits both platform users<br>and creators.<br><br>
      </div>
    </div>
  </div>
  <div class="level-item">
    <div id="card2" class="card">
      <div class="card-image">
        <figure class="image is-4by3">
          <img id="synthmtn" src="/Synth_Mtn.jpg">
        </figure>
      </div>
      <header class="card-header-title">
        <p class="card-header-title">
          What is the $TIPTOP token?
        </p>
      </header>
      <div id="text4" class="content">
        <br>
        1 $TIPTOP token is awarded daily to the creator of the Tip-Top post that<br>receives the most user engagement.<br><br>
        $TIPTOP has a supply of 1000 tokens and can be spent to redeem any<br>previously-released NFT, incrementing the NFT's supply hard-cap by 1.<br><br>
        This dynamic positions $TIPTOP as a <u>ceiling index</u> for the most valuable<br>NFTs on the platform.<br><br>
        The supply increase from $TIPTOP redemption can only happen once<br>for each unique NFT. Spent $TIPTOP is deposited back into the reward<br>pool from which it was issued for redistribution to creators.<br><br>
      </div>
    </div>
  </div>
</div>
<div id='level3' class="level">
  <div class="container">
    <div class="level">
      <div class="level-item">
        <div id="card3" class="card">
          <header class="card-header-title">
            <p class="card-header-title">
              What is the $TOPCAT token?
            </p>
          </header>
          <div id="text5" class="content">
            <br>
            Category token, or $TOPCAT, is an inflationary token awarded to LP providers. Category token is used to add content categories<br>to the Tip-Top platform.<br><br>
            Each time a new category is created, the spent category tokens will be deposited into a pool. A portion of $TOPCAT spent will<br>be burned permanently,
            a portion will be airdropped to platform users (post "likers"), and a portion will remain in the pool.<br><br>If $TOPCAT ever achieves a greater marketcap than $TIPTOP,
            the remaining $TOPCAT pool tokens will be used to purchase<br>$TIPTOP at market value. This creates a one-way peg between $TOPCAT and $TIPTOP, which ensures creator
            value is prioritized<br>on the platform.<br><br>Category will target an issuance of 1,000,000,000 tokens per year.<br><br>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
<section class="footer has-text-centered">
  <a
  id='wplink'
  href="/Tip-Top_one-pager.pdf"
  target="_blank"
  >
  READ THE WHITEPAPER
</a>
</section>
</section>
</template>

<script>
export default {
  data () {
    return {
      carousels: [
        { text: 'NFT 1', image: '/Synth_Mtn_footer.jpg' },
        { text: 'NFT 2', image: '/Synth_Mtn_footer.jpg' },
        { text: 'NFT 3', image: '/Synth_Mtn_footer.jpg' },
        { text: 'NFT 4', image: '/Synth_Mtn_footer.jpg' }
      ]
    }
  }
}
</script>
