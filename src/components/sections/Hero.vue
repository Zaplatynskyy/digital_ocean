<template>
    <div class="hero">
        <div class="container">
            <div class="row gy-2">
                <div class="col-12 col-sm-7">
                    <h2>The simplest cloud platform for developers & teams</h2>
                    <p>Deploy, manage, and scale cloud applications faster and more efficently on DigitalOcean. We make managing infrastructure easy for teams and business, whether you're running one virtual machine or ten thousand.</p>
                </div>
                <div class="col-12 col-sm-5 offset-lg-1 col-lg-4">
                    <form class="box">
                        <h3 class="form_title">Deploy your app in seconds.</h3>
                        <h3 class="form_subtitle">Get started now.</h3>

                        <input type="text" placeholder="Email">
                        <input type="password" placeholder="Password">

                        <div class="btn btn_create">Create your account</div>
                        <div class="btn btn_login">Sign up with google</div>

                        <div class="form_footer">By signing up you agree to the <a href="#">Term of Service</a></div>
                    </form>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name : 'Hero'
}
</script>

<style lang="scss">
@import '~bootstrap/scss/bootstrap-grid.scss';
@import '../../assets/style/variables.scss';


    .hero {
        background-image: url('../../assets/img/bg-banner-home.jpg');
        background-position: center;
        background-size: cover;
        padding: 50px 0;

        h2 {
            color: white;
        }

        p {
            color: #bbcdff;
            line-height: 1.5rem;
            margin-top: 10px;
        }

        .box {
            text-align: center;
            background-color: #fff;
            border-radius: 5px;
            padding: 20px 10px;

            .form_subtitle {
                color: $primary_color;
                margin: 5px 0;
            }

            input {
                width: 100%;
                border: 1px solid #eeeeee;
                border-radius: 5px;
                margin: 5px 0;
                padding: 5px;
            }

            .btn_create {
                color: white;
                background-color: #579aff;
            }

            .btn_login {
                color: #626262;
                box-shadow: 2px 2px 6px -3px #000000;;
            }

            .form_footer {
                font-size: .8rem;
                margin: 10px 0;
            }
        }
    }

    @media screen and (min-width : 576px) {
        h2 {
            font-size: 1.8rem;
        }
    }

    @media screen and (min-width : 768px) {
        h2 {
            font-size: 2rem;
        }
    }

    @media screen and (min-width : 992px) {
        body {
            font-size: 20px;
        }
    }
</style>