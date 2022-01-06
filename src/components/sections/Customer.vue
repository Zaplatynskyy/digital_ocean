<template>
    <section id="customer">
        <div class="title">Innovative business trust digitalocean</div>

        <div class="container">
            <div class="row gy-2 py-3">
                <div class="col-6 col-md-2"><img src="../../assets/img/docker.svg" alt="docker"></div>

                <div class="col-6 col-md-2"><img src="../../assets/img/gitlab.svg" alt="gitlab"></div>

                <div class="col-6 col-md-2"><img src="../../assets/img/slack.svg" alt="slack"></div>

                <div class="col-6 col-md-2 hashicorp"><img src="../../assets/img/hashicorp.svg" alt="hashicorp"></div>

                <div class="col-6 col-md-2 hashicorp"><img src="../../assets/img/hashicorp.svg" alt="hashicorp"></div>
                
                <div class="col-6 col-md-2"><img src="../../assets/img/splunk.svg" alt="splunk"></div>
            </div>
        </div>

        <div class="stories">
            <a href="#">
                View customer stories
                <i class="fas fa-greater-than"></i>
            </a>
        </div>
    </section>
</template>

<script>
export default {
    name : 'Customer'
}
</script>

<style lang="scss" scoped>
@import '~bootstrap/scss/bootstrap-grid.scss';
@import '../../assets/style/variables.scss';

    #customer {
        background-color: $secondary_color;

        .title {
            font-size: .8rem;
            font-weight: bold;
            text-align: center;
            text-transform: uppercase;
            color: #6f7b97;
        }

        .row {
            div {
                text-align: center;
            }
        }

        .stories {
            text-align: center;

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
    }

    @media screen and (min-width : 768px) {
        #customer {

            .row {
                div {
                    display: flex;
                    align-items: center;
                    img {
                        width: 100%;
                    }
                }
            }
        }
    }
</style>