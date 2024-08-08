# About
This project is for getting started with ShadCN in Vue.js.
Follow this tutorial to [get started](https://www.shadcn-vue.com/docs/installation/vite.html) 

# Snipets
- add button
```bash
npx shadcn-vue@latest add button
```
- implement this component
```ts
<script setup lang="ts">
import { Button } from '@/components/ui/button'
</script>

<template>
  <div>
    <Button>Click me</Button>
  </div>
</template>
```