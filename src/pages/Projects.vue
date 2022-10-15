<template>
    <div>
       <navbar />
       <section class="Projects">
   
        <h1 class="heading">Game<span> Play</span> </h1>
        <p> ตัวอย่าง gameplay: {{project_name}} {{project_detail}}</p>
        <br>
        
<div class="content">
    <p style="text-align: center;"><iframe width="1280" height="720" src="https://youtube.com/embed/Voy2LozpLj0" title="Noot Noot" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></p>
        </div>
   
   </section>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue';
   export default {
       components: { Navbar },
       data() {
        return {
            project_name: 'โดย',
            project_detail: 'Rubsarb',
        }
       }
   }

</script>

<style>

</style>