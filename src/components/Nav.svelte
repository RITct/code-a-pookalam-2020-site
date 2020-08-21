<script>
  export let segment;
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

<nav>
  <div class="imgContainer">
    <img src="/thrit.png" />
  </div>
  <div class="flow"></div>
  <div class="item">code-a-pookalam</div>
  <div class="item"><a href="#GUIDELINES">guidelines</a></div>
  <div class="item">entries</div>
  <div class="item social">
    <div>
      <a><img src="/insta.png" /></a>
    </div>
    <div>
      <a><img src="/fb.png" /></a>
    </div>
  </div>
</nav>
