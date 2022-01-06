<template>
    <section id="development">
        <div class="container">
            <h2 class="title_section">Development teams love DigitalOcean</h2>

            <div class="slider">
                <div class="image">
                    <i class="fas fa-chevron-left arrow"></i>
                    <div class="slider_box">
                        <img src="../../assets/img/rockerbox.png" alt="rockerbox">
                        <p>"We have been able to make scaling the technical infrastructure of our business cost effective end efficient."</p>
                        <div class="name_founder">Rick O'Toole</div>
                        <div class="info_name">Co-founder and CTO</div>
                        <a href="#">
                            View customer stories
                            <i class="fas fa-greater-than"></i>
                        </a>
                    </div>
                    <i class="fas fa-chevron-right arrow active"></i>
                </div>
                <div class="dots">
                    <span class="dot active"></span>
                    <span class="dot"></span>
                    <span class="dot"></span>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name : 'Development'
}
</script>

<style lang="scss">
@import '../../assets/style/variables.scss';

    #development {
        background-color: $secondary_color;

        .slider {
            text-align: center;
            padding-top: 100px;

            .image {
                display: flex;
                justify-content: center;
                align-items: center;

                .slider_box {
                    width: 70%;
                    background-color: #fff;
                    padding: 60px 0;

                    img {
                        width: 100%;
                        max-width: 700px;
                    }

                    p {
                        color: $primary_text;
                        margin: 10px 0;
                    }

                    .name_founder {
                        font-size: .8rem;
                        font-weight: bold;
                    }

                    .info_name {
                        font-size: .8rem;
                        margin-bottom: 20px;
                    }

                    a {
                        font-size: .8rem;
                        text-decoration: none;
                        
                        &:hover {
                            text-decoration: underline;
                        }

                        i {
                            font-size: .7rem;
                            margin: 0 5px
                        }
                    }
                }

                i.arrow {
                    font-size: 30px;
                    color: #6f7b97;
                    margin: 10px;
                    display: none;

                    &.active {
                        color: #031c4e;
                    }
                }
            }

            .dots {
                margin-top: 50px;
                .dot {
                    width: 10px;
                    height: 10px;
                    border: 1px solid $primary_color;
                    border-radius: 50%;
                    margin: 3px;
                    display: inline-block;

                    &.active {
                        background-color: $primary_color;
                    }
                }
            }
        }
    }

    @media screen and (min-width : 576px) {
        #development {
            .slider {
                .image {

                    .slider_box {
                        width: 60%;
                    }

                    i.arrow {
                        color: #6f7b97;
                        display: block;
                    }
                }
            }
        }
    }
</style>