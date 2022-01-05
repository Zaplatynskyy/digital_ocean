<template>
    <section id="designed">
        <div class="container">
            <h2 class="title_section">Designed for developers</h2>
            <p class="info_section">Build more and spend less time managing your infrastructure with our easy-to-use control panel and API.</p>

            <div class="slider">
                <div class="image">
                    <i class="fas fa-chevron-left"></i>
                    <img src="../../assets/img/slide.jpg" alt="slide digital ocean">
                    <i class="fas fa-chevron-right active"></i>
                </div>
                <span class="slider_text">Create compute server in 55 seconds or less.</span>
                <div class="dots">
                    <span class="dot active"></span>
                    <span class="dot"></span>
                    <span class="dot"></span>
                    <span class="dot"></span>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name : 'Designed'
}
</script>

<style lang="scss">
@import '../../assets/style/variables.scss';

    #designed {
        background-color: $secondary_color;

        .slider {
            text-align: center;
            padding-top: 100px;

            .image {
                display: flex;
                justify-content: center;
                align-items: center;

                img {
                    width: 80%;
                }

                i {
                    font-size: 30px;
                    color: #6f7b97;
                    margin: 10px;
                    display: none;

                    &.active {
                        color: #031c4e;
                    }
                }
            }

            .slider_text {
                width: 80%;
                font-size: .9rem;
                padding: 10px;
                margin: 0 auto;
                display: block;
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
        #designed {
            .slider {
                .image {

                    img {
                        width: 70%;
                    }

                    i {
                        color: #6f7b97;
                        display: block;
                    }
                }
            }
        }
    }
</style>