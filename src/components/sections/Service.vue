<template>
    <section id="service">
        <div class="container">
            <h2 class="title_section">Service your customers around the world from 12 regions.</h2>

            <div class="row gy-4 py-2 gx-lg-5">
                <ul class="col-12 col-lg-6">
                    <li>
                        <div class="acronym">ams2</div>
                        <div class="country_name">Amsterdam, Netherlands</div>
                        <a href="#">
                            Test speed
                            <i class="fas fa-greater-than"></i>
                        </a>
                    </li>
                    
                    <li>
                        <div class="acronym">ams3</div>
                        <div class="country_name">Amsterdam, Netherlands</div>
                        <a href="#">
                            Test speed
                            <i class="fas fa-greater-than"></i>
                        </a>
                    </li>

                    <li>
                        <div class="acronym">blr1</div>
                        <div class="country_name">Bangalore, India</div>
                        <a href="#">
                            Test speed
                            <i class="fas fa-greater-than"></i>
                        </a>
                    </li>

                    <li>
                        <div class="acronym">fra1</div>
                        <div class="country_name">Frankurt, German</div>
                        <a href="#">
                            Test speed
                            <i class="fas fa-greater-than"></i>
                        </a>
                    </li>

                    <li>
                        <div class="acronym">lon1</div>
                        <div class="country_name">London, UK</div>
                        <a href="#">
                            Test speed
                            <i class="fas fa-greater-than"></i>
                        </a>
                    </li>

                    <li>
                        <div class="acronym">nyc1</div>
                        <div class="country_name">New York, USA</div>
                        <a href="#">
                            Test speed
                            <i class="fas fa-greater-than"></i>
                        </a>
                    </li>
                </ul>

                <ul class="col-12 col-lg-6">
                    <li>
                        <div class="acronym">ams2</div>
                        <div class="country_name">Amsterdam, Netherlands</div>
                        <a href="#">
                            Test speed
                            <i class="fas fa-greater-than"></i>
                        </a>
                    </li>
                    
                    <li>
                        <div class="acronym">ams3</div>
                        <div class="country_name">Amsterdam, Netherlands</div>
                        <a href="#">
                            Test speed
                            <i class="fas fa-greater-than"></i>
                        </a>
                    </li>

                    <li>
                        <div class="acronym">blr1</div>
                        <div class="country_name">Bangalore, India</div>
                        <a href="#">
                            Test speed
                            <i class="fas fa-greater-than"></i>
                        </a>
                    </li>

                    <li>
                        <div class="acronym">fra1</div>
                        <div class="country_name">Frankurt, German</div>
                        <a href="#">
                            Test speed
                            <i class="fas fa-greater-than"></i>
                        </a>
                    </li>

                    <li>
                        <div class="acronym">lon1</div>
                        <div class="country_name">London, UK</div>
                        <a href="#">
                            Test speed
                            <i class="fas fa-greater-than"></i>
                        </a>
                    </li>

                    <li>
                        <div class="acronym">nyc1</div>
                        <div class="country_name">New York, USA</div>
                        <a href="#">
                            Test speed
                            <i class="fas fa-greater-than"></i>
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name : "Service"
}
</script>

<style lang="scss">
@import '../../assets/style/variables.scss';

    #service {
        background: rgb(0,30,154);
        background: linear-gradient(0deg, rgba(0,30,154,1) 50%, rgba(0,72,198,1) 100%);

        h2 {
            color: white;
        }

        ul {

            li {
                padding: 20px 10px;
                display: flex;
                justify-content: space-between;

                &:not(:last-child) {
                    border-bottom: 1px solid white;
                }
                

                .acronym {
                    font-size: .9rem;
                    text-transform: uppercase;
                    color: white;
                }

                .country_name {
                    font-size: .9rem;
                    color: #a9bbe6;
                    flex-grow: .5;
                }

                a {
                    font-size: .8rem;
                    text-decoration: none;
                    color: #00d5d1;
                    
                    &:hover {
                        text-decoration: underline;
                    }

                    i {
                        font-size: .6rem;
                        margin: 0 5px
                    }
                }
            }
        }
    }
</style>