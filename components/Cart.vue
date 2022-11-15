<template>
    <div>
         <div class="container mt-3">
             <div class="col-12 ">
                  <h1 class="text-center about_heading">About Me !</h1>
                  <p class="para">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet accusamus doloremque ab earum illum quae officiis nobis ipsum! Facere, doloremque.</p>
             </div>
         </div>
        <div class="container mt-5">
            <div class="row d-flex">
                <div class="col-sm-6 col-md-4 align-self-center">
                    <div class="card border-info mb-3" style="max-width: 18rem;">
                        <div class="card-header align-self-center">
                            <h3><i class="fa-brands fa-connectdevelop"></i></h3>
                        </div>
                            <div class="card-body">
                            <h3 class="card-title text-center text-info">Developer</h3>
                            <p class="card-text">Some quick example text to build on the card title and make up the bulk
                                of the
                                card's content.</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm-6 col-md-4 align-self-center">
                    <div class="card border-info mb-3" style="max-width: 18rem;">
                        <div class="card-header align-self-center">
                            <h3><i class="fa-brands fa-codepen"></i></h3>
                        </div>
                            <div class="card-body">
                            <h3 class="card-title text-center text-info">Developer</h3>
                            <p class="card-text">Some quick example text to build on the card title and make up the bulk
                                of the
                                card's content.</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm-6 col-md-4 align-self-center">
                    <div class="card border-info mb-3" style="max-width: 18rem;">
                        <div class="card-header align-self-center">
                            <h3><i class="fa-solid fa-code-branch"></i></h3>
                        </div>
                            <div class="card-body">
                            <h3 class="card-title text-center text-info">Developer</h3>
                            <p class="card-text">Some quick example text to build on the card title and make up the bulk
                                of the
                                card's content.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
 export default{
    name:'cart',

 }
</script>

<style scoped>
.about_heading{
    color: #839192;
    text-decoration: underline;
    text-decoration-color:#515A5A ;
    cursor: pointer;
}
.para{
    color: #283747 ;
    width: 800px;
    text-align: center;
    margin-left: 150px;
}
</style>