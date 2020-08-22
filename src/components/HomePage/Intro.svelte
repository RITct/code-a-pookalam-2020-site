<style>
  .container {
    height: 95vh;
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: "consolas";
    font-size: 4em;
    flex-direction: column;
  }
  .pookalam{
    background-image: url("/svg/pookalam.svg");
    height: 75vh;
    width: 75vh;
    max-width: 800px;
    max-height: 800px;
    position: absolute;
    right: 0;
    top: 0;
    background-repeat: no-repeat;
    background-size: contain;
    background-position: center;
  }
  .writing{
    margin-left: 2em;
    align-self: flex-start;
  }
  .span{
    font-size: 0.5em;
    font-family: "raleway";
    font-weight: 600;
  }
  @media only screen and (max-width: 1200px){
    .pookalam{
      height: 50vh;
      width: 50vh;
    }
    .container{
      font-size: 2.5em;
    }
  }
  @media only screen and (max-width: 720px) {
    .pookalam{
      position: relative;
      top: 0px;
      width: 100%;
      height: 100%;
      max-width: 280px;
      max-height: 280px;
    }
    .container{
      align-items: flex-end;
      justify-content: flex-start;
    }
    .writing{
      align-self: center;
      margin-left: 0;
      margin-top: 1em;
    }
  }
</style>

<div class="container">
  <div class="pookalam"/>
  <div class="writing">
    <div class="span">Unleash your inner mallu and</div>
    <h2>
      code a <br />
      pookalam;
    </h2>
  </div>
</div>
