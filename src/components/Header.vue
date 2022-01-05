<template>
    <header class="container">
        <div class="logo">
            <img src="../assets/img/logo.png" alt="">
        </div>

        <div class="bars">
            <i class="fas fa-bars"></i>
        </div>

        <nav class="links production">
            <ul>
                <li>Products<i class="fas fa-angle-down"></i></li>
                <li>Customers</li>
                <li>Community<i class="fas fa-angle-down"></i></li>
                <li>Pricing</li>
            </ul>
        </nav>

        <nav class="links user">
            <ul>
                <li>Docs</li>
                <li>Support<i class="fas fa-angle-down"></i></li>
                <li>Login</li>
                <li class="sign_up">Sign Up</li>
            </ul>
        </nav>          
    </header>
</template>

<script>
export default {
    name : 'Header'
}
</script>

<style lang="scss">
@import '../assets/style/variables.scss';

    header {
        height: 60px;
        background-color: white;
        display: flex;
        justify-content: space-between;
        align-items: center;

        .logo {
            height: 25px;
            img {
                height: 100%;
            }
        }

        .bars {
            i {
                color: $primary_color;
            }
        }

        .links {
            display: none;

            ul {
                li {
                    font-size: .8rem;
                    margin: 0 5px;
                    display: inline-block;
                    cursor: pointer;

                    i {
                        margin-left: 2px;
                    }

                    &.sign_up {
                        color: $primary_color;
                        border: 1px solid $primary_color;
                        border-radius: 5px;
                        padding: 5px;
                    }
                }
            }
        }
    }

    @media screen and (min-width : 768px) {
        header {
            .bars {
                 display: none;
            }

            .links {
                display: block;
            }
        }
    }

    @media screen and (min-width : 992px) {
        header {

            .links {
                ul {
                    li {
                        font-size: .9rem;
                        margin: 0 10px;
                    }
                }
            }
        }
    }
</style>