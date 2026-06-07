<template>
  <div class="services">
    <h1>Наши услуги</h1>
    <div class="service-list">
      <div class="service-item">
        <h2>Услуга1</h2>
        <p>Оп1</p>
      </div>
      <div class="service-item">
        <h2>Услуга2</h2>
        <p>Оп2</p>
      </div>
      <div class="service-item">
        <h2>Услуга3</h2>
        <p>Оп3</p>
      </div>
    </div>
  </div>
</template>

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
