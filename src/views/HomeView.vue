<template>
  <div class="home-view">
    <div class="left-section">
      <p class="today-text">Today.</p>
    </div>
    <div class="right-section">
      <p class="sleep-text">잠은 푹자자 -희성-</p>
    </div>
    <div class="center-section">
      <p class="items-text">플라스틱 종이 병 캔</p>
      <div class="numbers">
        <p>72</p>
        <p>60</p>
        <p>30</p>
        <p>89</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.home-view {
  background-color: #49B166;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
}

.left-section, .right-section, .center-section {
  text-align: center;
}

.today-text {
  color: #fff;
  font-family: 'Giants', sans-serif;
  font-size: 20px;
  font-weight: regular;
  position: absolute;
  top: 160px;
  left: 300px;
}

.sleep-text {
  color: #fff;
  font-family: 'sagak-sagak', sans-serif;
  font-size: 28px;
  font-weight: normal;
  position: absolute;
  top: 160px;
  right: 300px;
}

.items-text {
  color: #fff;
  font-family: 'Giants', sans-serif;
  font-size: 40px;
  font-weight: regular;
  margin-bottom: 5px;
  letter-spacing: 3px; 
}

.numbers {
  display: flex;
  justify-content: space-between;
}

.numbers p {
  font-family: 'Giants', sans-serif;
  font-size: 40px;
  font-weight: bold;
  color: #fff;
  margin: 0 20px;
}
</style>
