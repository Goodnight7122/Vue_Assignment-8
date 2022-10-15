<template>
    <div>
        <Navbar />

           <section class="About">

        <h1 class="heading"> About </h1>

        
        <div class="row">

                <div class="w3">

                 <p>Game Info</p>

                </div>

                <div class="box">
                        <h3> <span>Studio : </span> Porcelain Fortress </h3>
                        <h3> <span>Release Date : </span> Feb 28, 2019 </h3>
                        <h3> <span>Platform : </span> PC , Playstation , Xbox , Nintendo</h3>
                        <h3> <span>Price : </span> 229 baht </h3>
                    </div>

                    <div class="box">
                        <h3> <span>Max Player : </span> 4 </h3>
                        <h3> <span>Singleplay : </span> Yes (can add ai) </h3>
                        <h3> <span>Time per game : </span> 15-20 minutes while a Marathon game can last for up to 3 hours. </h3>
                        <h3> <span>Type : </span> Boardgame </h3>
                    </div>  
                        
            </div>

        </section>

    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue';
   export default {
       components: { Navbar }
}
</script>

<style>
</style>