<template>
    <section id="mediums">
        <div class="container">
            <h1>compose();</h1>
            <div class="row">
                <div class="col-md-4">
                    <div class="thumbnail">
                        <a :href="`${publicPath}palm.jpg`" target="_blank">

                            <img src="../../public/palm.jpg" alt="palm tree" style="width:100%">
                            <div class="caption">
                                <p>
                                    Dominican Flora
                                </p>
                            </div>
                        </a>
                    </div>
                </div>

                <div class="col-md-4">
                    <div class="thumbnail">
                        <a :href="`${publicPath}arch.jpg`" target="_blank">
                            <img src="../../public/arch.jpg" alt="St. Louis Gateway Arch" style="width:100%">
                            <div class="caption">
                                <p>
                                    Gateway
                                </p>
                            </div>
                        </a>
                    </div>
                </div>

                <div class="col-md-4">
                    <div class="thumbnail">
                        <a :href="`${publicPath}susp.jpg`" target="_blank">
                            <img src="../../public/susp.jpg" alt="suspension bridge in Cape Girardeau, MO" style="width:100%">
                            <div class="caption">
                                <p>
                                    Cape Girardeau
                                </p>
                            </div>
                        </a>
                    </div>
                </div>

            </div>
        </div><!--uppermost container-->

        <div class="container">
            <div class="row">
                <div class="col-xs-12 col-sm-12 col-md-6 col-lg-6 mt-3">
                    <div class="iframe-container">
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/b0YmoycNug0" frameborder="0"
                                allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </div>
                    <div class="caption">
                        <p>
                            Legacy Arts
                        </p>
                    </div>
                </div>

                <div class="col-xs-12 col-sm-12 col-md-6 col-lg-6 mt-3">
                    <div class="iframe-container">
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/dOc2bY0cihk" frameborder="0"
                                allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </div>
                    <div class="caption">
                        <p>
                            Squirrel Track
                        </p>
                    </div>
                </div>

            </div>
        </div>

        <div class="container">
            <div class="row">
                <div class="col-md-6">
                    <div class="thumbnail">
                        <a :href="`${publicPath}bear.jpg`" target="_blank">

                            <img src="../../public/bear.jpg" alt="wooden bear statue" style="width:100%">
                            <div class="caption">
                                <p>
                                    The Bear
                                </p>
                            </div>
                        </a>
                    </div>
                </div>

                <div class="col-md-6">
                    <div class="thumbnail">
                        <a :href="`${publicPath}codyClark.jpg`" target="_blank">
                            <img src="../../public/codyClark.jpg" alt="artistic double exposure photo of two men" style="width:100%">
                            <div class="caption">
                                <p>
                                    The Dons
                                </p>
                            </div>
                        </a>
                    </div>
                </div>



            </div><!-- row -->
        </div><!--lowermost container-->

    </section>
</template>

<script>
    export default {
        name: "mediums",
        data () {
            return {
                publicPath: process.env.BASE_URL
            }
        },
    }
</script>

<style scoped>
    .iframe-container{
        position: relative;
        width: 100%;
        padding-bottom: 56.25%;
        height: 0;
    }
    .iframe-container iframe{
        position: absolute;
        top:0;
        left: 0;
        width: 100%;
        height: 100%;
    }

</style>