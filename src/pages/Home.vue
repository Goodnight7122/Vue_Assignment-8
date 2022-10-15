<template>
 <div>
    <navbar />
    <section class="home">

<div class="image">
    <img src="images/profile.png" alt="">
</div>

<div class="content">
    <h3>{{name}}</h3>
    <span>"{{detail}}"</span>
    <p>{{content}}</p>
    <a href="https://www.youtube.com/watch?v=jqunKh27m4M" class="btn"> Trailer <i class="fas fa-user"></i> </a>
    <br>
    <a href="https://store.steampowered.com/app/829660/No_Time_to_Relax/" class="btn"> Check it out <i class="fas fa-user"></i> </a>
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
            name: 'No time to Relax',
            detail: 'เป็นเกมแนวบริหารชีวิต',
            content: 'เกมนี้ผู้เล่นจะได้รับบทเป็นคนที่อาศัยอยู่ในเมืองหนึ่ง ซึ่งต้องบริหารชีวิตทั้งด้านการเงิน สุขภาพ ความรู้ และความสุขเพื่อให้ได้คะแนนมากที่สุด เล่นได้พร้อมกันสูงสุด 4 คน ใน 1 ตาของผู้เล่นจะเท่ากับ 1 สัปดาห์ในเกม ผู้เล่นจะต้องทำกิจกรรมต่างๆ ไม่ว่าจะเป็นการกินข้าวเพื่อให้ได้มาซึ่งพลังงาน การทำงานเพื่อให้ได้เงิน หรือการซื้อของเพื่อให้ได้ความสุข ซึ่งจะจำกัดด้วยพลังงาน นั้นทำให้ผู้เล่นแต่ละคนสามารถหาวิธีเล่นที่ไม่เหมือนกันได้ สรุปแล้วเกมนี้เป็นเกมที่ผู้เล่นจะสามารถหาวิธีการเล่นของตัวเองได้ ไม่ว่าจะทำงานเพื่อจะหาซื้อของเพื่อความสุข หรือจะทำทุกอย่างในตาเดียวก็ได้ นั่นขึ้นอยู่กับคุณ แต่ก็ต้องระวังเพราะเพื่อนอาจจะแกล้งคุณได้ ลองเล่นดูสักครั้งแล้วจะติดใจ และสามารถเล่นออนไลน์กับคนอื่นได้ด้วย เกมนี้มีขายบนSteamในราคา229บาท'
        }
    }
}
</script>

<style>

</style>