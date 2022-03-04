<template>
<div class="row">
  <div class="col-md-2 col-xs-1"></div>
  <div class="col-md-8 col-xs-10">
    <q-input
        v-model="search"
        bg-color="grey-1"
        debounce="500"
        dense
        filled
        placeholder="請輸入城市或地點"
        hint="Search by Stanley"
      >
        <template v-slot:append>
          <q-icon name="search" />
        </template>
    </q-input>
  </div>
  <div class="col-md-2 col-xs-1"></div>
</div>
</template>

<script>
export default {
  data () {
    return {
      search: ''
    }
  }
}
</script>
