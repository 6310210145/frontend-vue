<template>
 <v-container>
    <v-row>
        <v-col cols="12">
         <Student/>
        </v-col>
    </v-row>
 </v-container>
</template>

<script>
export default {
  components: {
    Student: () => import('../components/StudentTable.vue')
  }
}
</script>

<style>

</style>
