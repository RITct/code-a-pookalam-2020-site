<style>
    .container{
        display: flex;
        height: 150vh;
        flex-direction: column;
    }
    .row{
        display: flex;
        flex: 1;
    }
    .section2{
        justify-content: space-between;
        margin-top: 7em;
    }
    .bold{
        font-weight: bold;
    }
    .bg{
        height: 100%;
        width: 100%;
        background-repeat: no-repeat;
        background-size: contain;
        background-position: center;
    }
    .stick{
        flex: 1;
        background-image: url("/date-pc.png");
    }
    .prize{
        display: flex;
        justify-content: flex-start;
        align-items: flex-start;
        max-width: 600px;
    }
    .cat{
        display: flex;
        justify-content: flex-start;
        align-items: flex-start;
        max-width: 430px;
        border-top: 6px solid #A13E12;
        padding-top: 2.5em;
    }
    .about{
        flex:2;
        font-family: "raleway";
        font-size: 1.2em;
        font-weight: 500;
        line-height: 40px;
        max-width: 600px;
    }
    .thoranam{
        display: none;
    }
    @media only screen and (max-width: 720px) {
        .about{
            padding: 1em;
            font-weight: 500;
            padding: 0;
        }
        .about div:nth-child(2n-1){
            padding: 1em;
        }
        .thoranam{
        display: block;
        width: 100%;
        }
        .thoranam img{
            width: 100%;
        }
    }
    @media only screen and (max-width: 1200px) {
        .container{
            height: unset;
        }
        .stick{
            display:none;
        }
        .cat{
            display: none;
        }
        .prize{
            padding: 0 3em 0 3em;
            width: 100%;
            height: 100%;
        }
        .prize img{
            width: 100%;
            height: 100%;
        }
    }
</style>

<div class="container">
    <div class="row">
        <div class="bg stick"/>
        <div class="about">
            <div>
                <span class="bold">
                    Is there anything more integral to the Mallu experience than Onam (with the possible exception of porotta and beef)? So why not combine your love for coding, with your love for all things Onam ?
                </span>
            </div>
            <div class="thoranam"><img src="/thoranam.png" alt="thoranam"></div>
            <div style="margin-top: 3em;">
                This Onam season, TinkerHub RIT would like to give you the opportunity to do just that. Build the pookalam of your dreams using the GUI programming language of your choice for a chance to win prizes, in addition to brownie points for building a pookalam without plucking a single flower. So grab your laptop, put on your Onam jam and get coding!
            </div>
        </div>
    </div>
    <div class="row section2">
        <div class="cat">
            <img src="/svg/prize_cat.svg"/>
        </div>
        <div class="prize">
            <img src="/svg/prize.svg"/>
        </div>
    </div>
</div>