<template>
  <div>
    <h1>Shop page</h1>
    <ul>
      <li v-for="i in 10" :key="i">
        สินค้าทั้งหมด {{ i }}
        <nuxt-link
          :to="{name:'shop-id',
                params:{id:i},}"
        >
          รายละเอียด
        </nuxt-link>
      </li>
    </ul>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>
