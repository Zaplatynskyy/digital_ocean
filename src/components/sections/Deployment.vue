<template>
    <section id="deployment">
        <div class="container">
            <h2 class="title_section">Deploy and Scale seamlessly</h2>
            <p class="info_section">Our optimized configuration process saves your team when running and scaling distributed applications, Al & machine learning workloads, hosted services, client websites, or CI/CD environtemnts.</p>

            <div class="row gy-3 py-5">
                <div class="col-12 offset-sm-2 col-sm-4 offset-md-2 col-md-3">
                    <ul>
                        <li>Deploy</li>
                        <li>Manage</li>
                        <li>Secure</li>
                        <li>Scale</li>
                        <li>Monitor</li>
                    </ul>
                </div>

                <div class="col-12 col-sm-4 col-md-6">
                    <div class="row gy-3">
                        <div class="col-12 col-md-6">
                            <img src="../../assets/img/cluster-deploy.svg" alt="cluster deploy">
                            <h4>Cluster deployments</h4>
                            <p>Provision multiple Droplets (virtual machines) in seconds with our control panel, CLI, or directly against our API</p>
                        </div>

                        <div class="col-12 col-md-6">
                            <img src="../../assets/img/optimized-compute.svg" alt="optimized compute">
                            <h4>Optimized compute types</h4>
                            <p>Get the compute resources you need with Standard or Optimized Droplets.</p>
                        </div>

                        <div class="col-12 col-md-6">
                            <img src="../../assets/img/one-click.svg" alt="one click apps">
                            <h4>One-click apps</h4>
                            <p>Skip the install and configuration process with pre-biult open source images supporting Rails, Cassandra, Docker, and more.</p>
                        </div>

                        <div class="col-12 col-md-6">
                            <img src="../../assets/img/global.svg" alt="global abailability">
                            <h4>Global availability</h4>
                            <p>Deploy to any of our data center regions around the world.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name : 'Deployment'
}
</script>

<style lang="scss">
@import '~bootstrap/scss/bootstrap-grid.scss';
@import '../../assets/style/variables.scss';

    #deployment {
        
        .row {
            ul {
                padding: 2px 10px;
                border-left: 1px solid $secondary_text;

                li {
                    color: $secondary_text;
                    margin: 10px 0;
                }
            }

            img {
                width: 30px;
            }

            h4 {
                margin: 5px 0;
            }

            p {
                font-size: .9rem;
                color: $secondary_text;
            }
        }
    }

</style>