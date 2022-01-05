<template>
    <section id="features">
        <div class="container">
            <h2 class="title_section">The features your business needs</h2>

            <div class="row gy-3 py-3">
                <div class="col-12 col-sm-4">
                    <img src="../../assets/img/pred-pricing.svg" alt="pred pricing">
                    <h4>Predictable pricing</h4>
                    <p>Leave complex pricing structures behind. Always know what you'll pay per month with a flat, industry-leading pricing structure.</p>
                    <a href="#">
                        Pricing
                        <i class="fas fa-angle-right"></i>
                    </a>
                </div>

                <div class="col-12 col-sm-4">
                    <img src="../../assets/img/world-class.svg" alt="world class">
                    <h4>World-class service</h4>
                    <p>Free round-the-clock technical support for all customers. You'll feel the love.</p>
                    <a href="#">
                        Support
                        <i class="fas fa-angle-right"></i>
                    </a>
                </div>

                <div class="col-12 col-sm-4">
                    <img src="../../assets/img/reliable-platform.svg" alt="reliable platform">
                    <h4>Reliable platform</h4>
                    <p>More than 100.000 developer teams worldwide trust DigitalOcean to support their business with a 99.99% uptime SLA for all services.</p>
                    <a href="#">
                        Security
                        <i class="fas fa-angle-right"></i>
                    </a>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style lang="scss">
@import '../../assets/style/variables.scss';

    #features {
            
        .row {
            img {
                width: 30px;
            }

            h4 {
                margin: 5px 0;
            }

            p {
                font-size: .9rem;
                color: $secondary_text;
                padding-bottom: 5px;
            }

            a {
                font-size: .8rem;
                text-decoration: none;
                
                &:hover {
                    text-decoration: underline;
                }

                i {
                    margin: 0 5px
                }
            }
        }
    }
</style>