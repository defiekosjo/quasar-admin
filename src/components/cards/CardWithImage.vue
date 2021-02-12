<template>
  <div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
    <q-card class="my-card">
      <img :src="require('src/assets/empty_map.png')" style="max-height:750px;" />
        <div class="absolute-bottom-left bg-transparent q-ml-md">
          <div class="text-h5">Map showroom</div>
        </div>
      </q-img>
    </q-card>
  </div>
</template>

<script>
export default {
  name: "CardWithImage",
};
</script>