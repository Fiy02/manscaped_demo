<template>
<div>
    <div class="header">
        <div class="container">
            <div class="row">
                <div class="left-text col-md-8">
                    <a href="/">
                        <b>FREE boxers + toiletry bag + free Shipping</b>
                        <b>with the purchase of the PERFECT PACKAGE kit</b>
                    </a>
                </div>
                <div class="right-text col-md-4">
                    <a href="/">
                        <span>Get Limited Time Offer</span>
                    </a>
                </div>
            </div>
        </div>
    </div>
    <div class="navigation-bar">
        <div class="container">
            <div class="row">
                <div class="left-text col-md-2">
                    <img src="//cdn.shopifycdn.net/s/files/1/1383/0317/t/380/assets/logo-black.png?v=12627392707803563819" alt="">
                </div>
                <div class="col-md-8">
                    <div class="dropdown">
                        <a href="/">products</a>
                        <div class="dropdown-content">
                            <ul>
                                <li>
                                    <a href="/"><span>sets</span></a>
                                </li>
                                <li>
                                    <a href="/"><span>tools</span></a>
                                </li>
                                <li>
                                    <a href="/"><span>formulations</span></a>
                                </li>
                                <li>
                                    <a href="/"><span>lifestyle</span></a>
                                </li>
                            </ul>
                        </div>
                    </div>
                    <a href="/" id="casuse">our casuse</a>
                    <div class="dropdown-icon">
                        <a href="/">us</a>
                        <div class="dropdown-icon-content">
                            <ul>
                                <li>usa</li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="right-text col-md-2">
                    <a href="/">account</a>
                </div>
             </div>
        </div>
    </div>
</div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.header {
    top: 0;
    width: 100%;
    height: 70px;
    background: black;
    position: fixed;
    z-index: 999;
    .left-text {
        background-image: url(//cdn.shopifycdn.net/s/files/1/1383/0317/files/tag-special-offer_large.png?v=1577401152);
        background-repeat: no-repeat;
        background-size: 25%;
        background-position: center left;;
        a {
            display: block;
            padding-left: 220px;
            padding-top: 10px;
            padding-bottom: 10px;
            color: white;
            text-transform: uppercase;
            text-decoration: none;
            b {
                text-align: center;
                font-size: 17px;
                display: block;
                line-height: 25px;
            }
        }
    }
    .right-text {
        padding: 0;
        background-image: url(//cdn.shopifycdn.net/s/files/1/1383/0317/t/380/assets/arrow-right-white.png?v=14114415183759225239);
        background-size: 40px;
        background-repeat: no-repeat;
        background-position: center left;
        a {
            display: block;
            float: right;
            padding: 10px 0;
            text-decoration: none;
            color: #daaa00;
            span {
                font-size: 22px;
                display: inline-block;
                text-transform: uppercase;
                border: 1px solid #daaa00;
                padding: 10px 30px;
            }
        }
    }
}
.navigation-bar {
    margin-top: 70px;
    border-bottom: 1px solid #b9b9b9;
    .left-text {
        img {
            display: block;
            max-height: 20px;
            margin: 10px 0;
        }
    }
    .col-md-8 {
        margin: 10px 0;
        font-size: 18px;    
        text-align: right;
        a {
            color: black;
            text-decoration: none;
            text-transform: uppercase;
            font-family: fantasy;
        }
        .dropdown {
            position: relative;
            margin-right: 50px;
            display: inline-block;
        }
        .dropdown-content {
            width: 100%;
            position: absolute;
            display: block;
            ul {
                padding: 0;
                li {
                    display: inline-block;
                    text-align: center;
                    list-style-type: none;
                    a {
                        font-family: sans-serif;
                        font-size: 16px;
                        text-decoration: none;
                    }
                }
            }
        }
        .dropdown:hover .dropdown-content {
            display: block;
        }
        #casuse {
            text-decoration: none;
        }
        .dropdown-icon {
            margin-left: 120px;
            display: inline-block;
        }
        .dropdown-icon-content {
            display: none;
        }
    }
    .right-text {
        padding: 0;
        margin: 10px 0;
        background-image: url(//cdn.shopifycdn.net/s/files/1/1383/0317/t/380/assets/cart-icon.png?v=11276354948246297087);
        background-repeat: no-repeat;
        background-size: 20px;
        background-position: center right;
        a{
            padding-left: 50px;
            font-family: fantasy;
            font-size: 18px;
            color: black;
            text-transform: uppercase;
            text-decoration: none;
        }
    }
}
</style>