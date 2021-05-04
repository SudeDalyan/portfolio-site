<template>
    <div class="row">
        <div class="col-md-12">
            <h1 class="portfolio-head">Portfolio</h1>
            <div class="carousel-item active">

                <div class="col-md-3" style="float: left;margin-bottom: 30px;">
                    <div class="card mb-2">
                        <img class="card-img-top"
                            src="../assets/book (3).jpg"
                            alt="Card image cap">
                        <div class="card-body">
                            <h4 class="card-title">I translated it into different languages.</h4>
                            <a class="btn">More Information</a>
                        </div>
                    </div>
                </div>

                <div class="col-md-3" style="float:left; margin-bottom: 30px;">
                    <div class="card mb-2">
                        <img class="card-img-top"
                            src="../assets/book (4).jpg"
                            alt="Card image cap">
                        <div class="card-body">
                            <h4 class="card-title">I translated it into different languages.</h4>
                           
                            <a class="btn">More Information</a>
                        </div>
                    </div>
                </div>

                <div class="col-md-3" style="float:left;margin-bottom: 30px;">
                    <div class="card mb-2">
                        <img class="card-img-top"
                            src="../assets/book (2).jpg"
                            alt="Card image cap">
                        <div class="card-body">
                            <h4 class="card-title">I have written many books.</h4>
                            <a class="btn">More Information</a>
                        </div>
                    </div>
                </div>

                <div class="col-md-3" style="float:left;margin-bottom: 30px;">
                    <div class="card mb-2">
                        <img class="card-img-top"
                            src="../assets/book (1).jpg"
                            alt="Card image cap">
                        <div class="card-body">
                            <h4 class="card-title">I have been a columnist for many degides.</h4>
                            <a class="btn">More Information</a>
                        </div>
                    </div>
                </div>

            </div>


        </div>
    </div>

</template>

<script>
    export default {
        name: 'Portfolio',
        props: {
            msg: String
        }
    }
</script>