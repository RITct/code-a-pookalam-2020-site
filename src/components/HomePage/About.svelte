<style>
    .container{
        display: flex;
        height: 80vh;
        flex-direction: column;;
    }
    .bannerContainer{
        width: 100%;
        height: 100%;
        background-image: url("/thoranam.png");
        background-repeat: no-repeat;
        background-size: contain;
        background-position: center;
    }
    .row{
        display: flex;
    }
    .stick{
        flex: 1;
        background-image: url("/prize.png");
        height: 100%;
        width: 100%;
        background-repeat: no-repeat;
        background-size: contain;
        background-position: center;
    }
    .about{
        flex:2;
        font-family: "raleway";
        font-size: 1.2em;
        max-width: 600px;
    }
    @media only screen and (max-width: 720px) {
        .stick{
            display:none;
        }
        .about{
            padding: 1em;
            font-weight: 500;
        }
        .bannerContainer{
            background-image: url("/date.png");
            max-width: 280px;
            padding: 0.5em;
            display: flex;
            margin: 0 auto;
        }
    }
</style>

<div class="container">
    <div class="bannerContainer"/>
    <div class="row">
        <div class="stick"/>
        <div class="about">
            <p>
                Let Mahabali’s return to Earth this year let you and your family celebrate a prosperous onam! What better way to welcome his majesty than with a pookalam, with a twist :) .
            </p>
            <p>
                TinkerHub RIT presents <b>Code A Pookalam</b> contest! 
            </p>
            <p>
                Bring out your creativity by creating a pookalam design using any GUI Programming Language.
            </p>
            <p>
                Get Coding!
            </p>
        </div>
    </div>
</div>