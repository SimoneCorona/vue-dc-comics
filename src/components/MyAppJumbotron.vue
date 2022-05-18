<template>
    <footer>

        <section class="icons">
            <div class="container">
                <ul>
                    <li>
                        <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                        <p>DIGITAL COMICS</p>

                    </li>
                    <li>
                        <img src="../assets/img/buy-comics-merchandise.png" alt="">
                        <p>DC MERCHANDISE</p>
                    </li>
                    <li>
                        <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                        <p>SUBSCRIPTION</p>
                    </li>
                    <li>
                        <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                        <p>COMIC SHOP LOCATION</p>
                    </li>
                    <li>
                        <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                        <p>DC POWER VISA</p>
                    </li>
                </ul>
            </div>
        </section>

        <section class="banner">
            <div class="container">
                <div class="links-wrapper">
                    <div>
                        <ul>
                            <li>
                                <h1>DC COMICS</h1>
                            </li>
                            <li><a href="">Characters</a></li>
                            <li><a href="">Comics</a></li>
                            <li><a href="">Movies</a></li>
                            <li><a href="">TV</a></li>
                            <li><a href="">Games</a></li>
                            <li><a href="">Videos</a></li>
                            <li><a href="">News</a></li>
                        </ul>
                        <ul>
                            <li>
                                <h1>SHOP</h1>
                            </li>
                            <li><a href="">Shop DC</a></li>
                            <li><a href="">Shop DC Collectibles</a></li>
                        </ul>
                    </div>

                    <div>
                        <ul>
                            <li>
                                <h1>DC</h1>
                            </li>
                            <li><a href="">Terms Of Use</a></li>
                            <li><a href="">Privacy policy (New)</a></li>
                            <li><a href="">Ad Choices</a></li>
                            <li><a href="">Advertising</a></li>
                            <li><a href="">Jobs</a></li>
                            <li><a href="">Subscriptions</a></li>
                            <li><a href="">Talent Workshops</a></li>
                            <li><a href="">CPSC Certificates</a></li>
                            <li><a href="">Ratings</a></li>
                            <li><a href="">Shop Help</a></li>
                            <li><a href="">Contact Us</a></li>
                        </ul>
                    </div>
                    
                    <div>
                        <ul>
                            <li>
                                <h1>SITES</h1>
                            </li>
                            <li><a href="">DC</a></li>
                            <li><a href="">MAD Magazine</a></li>
                            <li><a href="">DC Kids</a></li>
                            <li><a href="">DC Universe</a></li>
                            <li><a href="">DC Power Visa</a></li>
                            
                        </ul>
                    </div>
                </div>

                <div class="banner-log">
                    <img src="../assets/img/dc-logo-bg.png" alt="">
                </div>
            </div>
        </section>

        <section class="footer-bottom">
            <div class="container">
                <div>
                    <span>
                        <a href="">SIGN-UP NOW!</a> 
                    </span>
                </div>
                <div class="follow-us">
                    <h1>FOLLOW US</h1>
                    <img src="../assets/img/footer-facebook.png" alt="">
                    <img src="../assets/img/footer-twitter.png" alt="">
                    <img src="../assets/img/footer-youtube.png" alt="">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                    <img src="../assets/img/footer-periscope.png" alt="">
                </div>
            </div>
        </section>
    </footer>
</template>

<script>
export default {
    name: 'MyAppJumbotron',
}
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

footer{
    color: white;
    position: relative;
    
    .icons{
        height: 100px;
        width: 100%;
        position: absolute;
        top: 0;
        z-index: 1000;
        background-color: $brand-primary-light-color;
        
        .container{
            ul{
                display: flex;
                line-height: 100px;
                justify-content: space-around;
                
                li{
                    display: flex;
                    justify-content: row;
                    align-items: center;

                img{    
                    height: 40px;
                    }
                p{
                    font-size: 0.8rem;
                    margin-left: 0.5rem;
                }
                }
            };
        }    
    }

    .banner{
        height: 560px;
        background-image: url(../assets/img/footer-bg.jpg);
        
        .container{
            display: flex;
            

            .links-wrapper{
                display: flex;
                align-self: center;
                padding: 120px 0;
                flex-grow: 1;
                
                div{
                    margin-right: 1.5rem;

                    ul{
                        margin-bottom: 1rem;

                        h1{
                            font-size: 1.2rem;
                            color: white;
                            margin-bottom: 0.5rem;
                        }
                        li{
                            margin-bottom: 0.3rem;

                            a{
                                color: gray;
                                font-weight: 300;
                            }
                        }
                    }
                }  
            }
        }
    }

    .footer-bottom{
        height: 80px;
        width: 100%;
        line-height: 80px;
        background-color: $brand-secondary-color;
        position: absolute;
        bottom: 0;
        z-index: 1000;

        .container{
            display: flex;
            flex-direction: row;
            align-items: center;
            
            a{
                color: white;
                border: 3px solid $brand-primary-color;
                padding: 0.5rem;
            }

            .follow-us{
                display: flex;
                flex-grow: 1;
                justify-content: flex-end;
                flex-direction: row;
                align-items: center;

                h1{
                    font-size: 1.2rem;
                    margin: 0 0.7rem;
                    color: $brand-primary-color;
                }
                
                img{
                    margin: 0 0.7rem;
                }
            }
        }
    }
}
</style>