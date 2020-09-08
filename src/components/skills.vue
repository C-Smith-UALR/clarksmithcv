<template>
    <section id="skills">
        <div class="container">
            <h2>Skill Set</h2>
            <div class="row">
                <div class="col-sm-12 col-md-6 col-lg-6">
                    <div class="card">
                        <div class="card-body">
                            <h4 class="card-title">Web Stacks</h4>
                            <p>Using javascript frameworks to design responsive, dynamic web applications.  Full stack development
                                of single-page apps on a variety of stacks: serverless, graphql, SQL, REST APIs.</p>
                            <a href="https://www.medzoar.com/" class="card-link">Medzoar</a>

                        </div>
                    </div>
                </div>

                <div class="col-sm-12 col-md-6 col-lg-6">
                    <div class="card">
                        <div class="card-body">
                            <h4 class="card-title">AI</h4>
                            <p>Leveraging Python libraries to set up and train neural networks(CNN, LTSM, ResNet), for applications in
                                image classification(MNIST), clinical diagnostics, and other models.
                            </p>
                            <a :href="`${publicPath}clarkSmithAiCert.pdf`" download>Certificate</a>

                        </div>
                    </div>
                </div>

                <div class="col-sm-12 col-md-6 col-lg-6">
                    <div class="card">
                        <div class="card-body">
                            <h4 class="card-title">Bioinformatics</h4>
                            <p>
                                Leveraging R libraries and Unix shell to study genomic data (ranges and sequences).
                                Manipulating dataframes and other data structures to build biological statistical models.
                                Building Linux machines.
                            </p>


                        </div>
                    </div>
                </div>

                <div class="col-sm-12 col-md-6 col-lg-6">
                    <div class="card">
                        <div class="card-body">
                            <h4 class="card-title">Legacy Arts</h4>
                            <p>
                               Employing a variety of mediums (poetry, photographs, videos, Dignity Therapy) to create
                               legacy objects for patients affected by serious illness.  Being a mirror that reflects dignity.
                            </p>
                            <a href="https://gatheringhope.github.io/" class="card-link">Gathering Hope</a>

                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>
</template>

<script>
    export default {
        name: "skills",
        data () {
            return {
                publicPath: process.env.BASE_URL
            }
        },
    }
</script>

<style scoped>

</style>