<template>
  <div class="services">
    <h1>Наши услуги</h1>
    <div class="service-list">
      <div class="service-item">
        <h2>Веб-разработка</h2>
        <p>Создание современных веб-сайтов и приложений</p>
      </div>
      <div class="service-item">
        <h2>Дизайн</h2>
        <p>Разработка уникального дизайна для вашего бизнеса</p>
      </div>
      <div class="service-item">
        <h2>Поддержка</h2>
        <p>Техническая поддержка и сопровождение проектов</p>
      </div>
    </div>
  </div>
</template>

<script setup>
// Логика компонента
</script>

<style scoped>
.services {
  text-align: center;
  margin-top: 50px;
}

.service-list {
  display: flex;
  justify-content: space-around;
  margin-top: 30px;
}

.service-item {
  text-align: left;
  padding: 20px;
  width: 30%;
}

h1 {
  color: #333;
}

h2 {
  color: #555;
  margin-bottom: 10px;
}

p {
  font-size: 16px;
  color: #666;
}
</style>
