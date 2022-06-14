<template>
  <div
    class=" entry-cointainer mb-3 pointer p-2"
    @click="$router.push({name: 'entry', params:{ id:10}})"
  >
    <!-- Titulo -->
    <div class="entry-title d-flex">
        <span class="text-success fs-5 fw-bold">12</span>
        <span class="mx-1 fs-5">Junio</span>
        <span class="mx-2 fw-light">2022 Domingo</span>
    </div>

    <div class="entry-description">
        lorem lorem consectetur ipsum adipisicing ipsum adipisicing sit consectetur sit elit consectetur dolor elit ipsum adipisicing sit sit elit. sit adipisicing adipisicing amet amet dolor ipsum dolor sit ipsum amet consectetur ipsum sit consectetur dolor sit amet lorem ipsum. amet ipsum lorem elit dolor ipsum ipsum ipsum ipsum dolor sit amet ipsum amet amet adipisicing elit adipisicing sit elit. amet elit elit adipisicing amet lorem lorem adipisicing adipisicing dolor amet ipsum lorem ipsum consectetur adipisicing ipsum lorem. ipsum ipsum lorem dolor adipisicing elit adipisicing dolor sit amet amet amet amet amet elit dolor.
    </div>

  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.entry-cointainer{
    border-bottom:1px solid #2c3e50;
    transition: 0.2s all ease-in;
    
    &:hover{
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2s all ease-in;
    }

    .entry-description {
        font-size: 12px;
    }
}

</style>