<template>
  <svg viewBox="0 0 155 113" fill="none" xmlns="http://www.w3.org/2000/svg">
    <path
      d="M58.8385 3.4903C61.1479 -0.5097 66.9214 -0.509709 69.2309 3.49029L126.822 103.24C129.131 107.24 126.244 112.24 121.625 112.24H6.44402C1.82522 112.24 -1.06154 107.24 1.24786 103.24L58.8385 3.4903Z"
      :fill="theme === 'dark' ? '#EDEDED' : '#1470DB'"
    />
    <path
      d="M97.1188 24.0956C99.4282 20.0956 105.202 20.0956 107.511 24.0956L153.236 103.293C155.545 107.293 152.658 112.293 148.039 112.293H56.5905C51.9717 112.293 49.0849 107.293 51.3943 103.293L97.1188 24.0956Z"
      :fill="theme === 'dark' ? '#FFFFFF' : '#2196F3'"
    />
    <path
      d="M62.9537 42.7761C65.2631 38.7761 71.0366 38.7761 73.346 42.7761L108.171 103.096C110.481 107.096 107.594 112.096 102.975 112.096H33.3244C28.7056 112.096 25.8188 107.096 28.1282 103.096L62.9537 42.7761Z"
      fill="#333333"
    />
    <path
      d="M88.4153 56.4814C90.7247 52.4814 96.4982 52.4813 98.8076 56.4813L125.74 103.13C128.05 107.13 125.163 112.13 120.544 112.13H66.6786C62.0598 112.13 59.1731 107.13 61.4825 103.13L88.4153 56.4814Z"
      fill="#333333"
    />
  </svg>
</template>

<script>
import { mapState } from 'vuex'

export default {
  computed: {
    ...mapState(['theme'])
  }
}
</script>
<style>
.NuxtLogo {
  animation: 1s appear;
  margin: auto;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
</style>
