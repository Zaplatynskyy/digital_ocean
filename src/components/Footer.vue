<template>
    <footer>
        <div class="top_footer">
            <h2 class="title_section">Get started now.</h2>
            <div class="btn btn_footer">Create your account</div>
        </div>
        <div class="bottom_footer">
            <div class="container">
                <div class="row gy-3">
                    <div class="col-12 col-md-4 copyright">
                        <img src="../assets/img/logo-small.svg" alt="logo digitalocean">

                        <div class="text_footer">
                            <div class="text_copyright">&#169; 2018 DigitalOcean, LLC. All rights reserved.</div>
                            <div class="text_made">Proudly made in NY</div>
                        </div>

                        <div class="social_icon">
                            <ul>
                                <li><a href="#"><i class="fab fa-twitter"></i></a></li>
                                <li><a href="#"><i class="fab fa-facebook-square"></i></a></li>
                                <li><a href="#"><i class="fab fa-instagram"></i></a></li>
                                <li><a href="#"><i class="fab fa-youtube"></i></a></li>
                                <li><a href="#"><i class="fab fa-linkedin"></i></a></li>
                            </ul>
                        </div>
                    </div>

                    <div class="col-12 col-md-8">
                        <div class="row gy-3">
                            <div class="col-12 col-sm-6 col-md-3">
                                <ul class="links_footer company">
                                    <li><a href="#">Company</a></li>
                                    <li><a href="#">About</a></li>
                                    <li><a href="#">Leadership</a></li>
                                    <li><a href="#">Link</a></li>
                                    <li><a href="#">Blog</a></li>
                                    <li><a href="#">Careers</a></li>
                                    <li><a href="#">Partner Network</a></li>
                                    <li><a href="#">Referral Program</a></li>
                                    <li><a href="#">Events</a></li>
                                    <li><a href="#">Press</a></li>
                                    <li><a href="#">Legal & Security</a></li>
                                </ul>
                            </div>

                            <div class="col-12 col-sm-6 col-md-3">
                                <ul class="links_footer products">
                                    <li><a href="#">Products</a></li>
                                    <li><a href="#">Droplets</a></li>
                                    <li><a href="#">Spaces</a></li>
                                    <li><a href="#">Kubernetes</a></li>
                                    <li><a href="#">Load Balancers</a></li>
                                    <li><a href="#">Block Storage</a></li>
                                    <li><a href="#">Tools & Integrations</a></li>
                                    <li><a href="#">One-Click Apps</a></li>
                                    <li><a href="#">API</a></li>
                                    <li><a href="#">Pricing</a></li>
                                    <li><a href="#">Documentation</a></li>
                                    <li><a href="#">Release Notes</a></li>
                                </ul>
                            </div>

                            <div class="col-12 col-sm-6 col-md-3">
                                <ul class="links_footer community">
                                    <li><a href="#">Community</a></li>
                                    <li><a href="#">Tutorials</a></li>
                                    <li><a href="#">Meetups</a></li>
                                    <li><a href="#">Q&A</a></li>
                                    <li><a href="#">Write for Donations</a></li>
                                    <li><a href="#">Droplets for Demos</a></li>
                                    <li><a href="#">Hatch</a></li>
                                    <li><a href="#">Shop Swag</a></li>
                                    <li><a href="#">Research Program</a></li>
                                    <li><a href="#">Currents Research</a></li>
                                    <li><a href="#">Open Source</a></li>
                                </ul>
                            </div>

                            <div class="col-12 col-sm-6 col-md-3">
                                <ul class="links_footer support">
                                    <li><a href="#">Support</a></li>
                                    <li><a href="#">Contact support</a></li>
                                    <li><a href="#">FAQ</a></li>
                                    <li><a href="#">Network Status</a></li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="answer">
                    <div class="img_answer">
                        <img src="../assets/img/shark.png" alt="">
                        <div class="num_answer">2</div>
                    </div>

                    <div class="text_answer">
                        Can i help answer any questions you have about DigitalOcean
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name : 'Footer'
}
</script>

<style lang="scss">
@import '../assets/style/variables.scss';

    .top_footer {
        background: rgb(0,30,154);
        background: linear-gradient(0deg, rgba(0,30,154,1) 50%, rgba(0,72,198,1) 100%);
        padding: 50px 0;

        h2 {
            color: white;
        }

        .btn_footer {
            width: 150px;
            text-align: center;
            color: #006aff;
            background-color: #fff;
            margin: 0 auto;
            margin-top: 20px;

        }
    }

    .bottom_footer {
        background-color: #031c4e;
        padding: 50px 0;
        
        .container {
            position: relative;
        }

        .copyright {
            img {
                width: 40px;
            }

            .text_footer {
                font-size: .9rem;
                margin: 5px 0;

                .text_copyright {
                    color: #8b94a9;
                }

                .text_made {
                    color: #5a6887;
                }
            }

            .social_icon {
                ul {
                    li {
                        margin: 0 5px;
                        display: inline-block;

                        i {
                            color: #7a859d;
                        }
                    }
                }
            }
        } 

        .links_footer {
            li:not(:first-child) {
                margin-bottom: 5px;
                
                a {
                    font-size: .9rem;
                    text-decoration: none;
                    color: #a6adbd;
                }
            }

            li:first-child {
                margin-bottom: 5px;
                
                a {
                    text-decoration: none;
                    color: white;
                    cursor: inherit;
                }
            }
        }

        .answer {
            position: absolute;
            bottom: -40px;
            left: 20px;

            .img_answer {
                width: 50px;
                height: 50px;
                line-height: 50px;
                background-color: #006aff;
                border-radius: 5px;
                position: relative;

                img {
                    width: 100%;
                    vertical-align: middle;
                }

                .num_answer {
                    width: 20px;
                    height: 20px;
                    line-height: 18px;
                    text-align: center;
                    font-size: 14px;
                    font-weight: bold;
                    color: white;
                    background-color: red;
                    border: 2px solid white;
                    border-radius: 50%;
                    position: absolute;
                    top: -6px;
                    right: -6px;
                }
            }

            .text_answer {
                width: 300px;
                line-height: 20px;
                font-size: .8rem;
                background-color: #fff;
                border-radius: 5px;
                padding: 5px;
                margin: 15px 0;
            }
        }
    }

</style>