<script>
  export let segment;
  let y = 0;
  let img;
  $: headerClass = updateClass(y);
  function updateClass(y) {
    if (img) {
      if (y > 100) {
        img.src = "/svg/logo.svg";
        img.style.top = 0;
      } else {
        img.src = "/thrit.png";
        img.style.top = "1em";
      }
    }
  }
</script>

<style>
  nav {
    display: flex;
    position: relative;
    top: 1em;
    align-items: center;
    background-color: #f1ebe0;
    z-index: 5;
    position: sticky;
  }
  .flow {
    flex-grow: 1;
  }
  .item {
    margin: 0.5em;
    font-family: "raleway-bold";
    display: flex;
    align-items: center;
    color: #6a2202;
  }
  .imgContainer {
    display: flex;
    justify-content: center;
    align-items: center;
    max-width: 160px;
    margin-left: 1em;
  }
  a {
    text-decoration: none;
  }
  @media only screen and (max-width: 720px) {
    nav {
      top: 0;
    }
    .item {
      display: none;
    }
    .social {
      display: flex;
    }
  }
</style>

<svelte:window bind:scrollY="{y}" />
<nav>
  <div class="imgContainer">
    <img bind:this="{img}" src="/thrit.png" />
  </div>
  <div class="flow"></div>
  <div class="item">code-a-pookalam</div>
  <div class="item"><a href="#GUIDELINES">guidelines</a></div>
  <div class="item">entries</div>
  <div class="item social">
    <div>
      <a href="https://instagram.com/tinkerhub.rit" target="_blank"><img src="/insta.png" /></a>
    </div>
    <div>
      <a href="https://www.facebook.com/TinkerHubRIT/" target="_blank"><img src="/fb.png" /></a>
    </div>
  </div>
</nav>
