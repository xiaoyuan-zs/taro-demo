<template>
  <view>
    <text>{{ msg }}</text>
  </view>
</template>

<script setup>
import { ref } from 'vue'
import './index.scss'

const msg = ref('Hello world')
</script>
