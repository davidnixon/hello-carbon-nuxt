<template>
  <cv-grid style="margin-top: 4rem">
    <cv-row>
      <cv-column>
        <cv-accordion >
          <cv-accordion-item v-for="n in 4" :key="`acc-item-${n}`" :id="n % 2 ? `acc-item-${n}` : ''">
            <template v-slot:title>Section {{n}} title </template>
            <template v-slot:content>
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
            </template>
          </cv-accordion-item>
        </cv-accordion>
      </cv-column>
    </cv-row>
  </cv-grid>
</template>
<script setup>

</script>


<style scoped lang="scss">

</style>
