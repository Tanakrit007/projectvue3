<script setup> 
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      เราได้รวบรวมช่องทีวีต่างๆมากมายเตรียมพร้อมให้คุณได้รับชมแล้ว
    </h3>
  </div>
</template>

<style scoped>
.greetings {
  position: absolute; /* จัดตำแหน่งแบบ absolute */
  top: 0; /* ตำแหน่งด้านบนสุด */
  left: 0; /* ตำแหน่งด้านซ้ายสุด */
  padding: 1rem; /* เพิ่ม padding เพื่อให้มีระยะห่างจากขอบ */
}

h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: left; 
}

@media (min-width: 1024px) {
  .greetings {
    padding: 2rem; 
  }
}
</style>
