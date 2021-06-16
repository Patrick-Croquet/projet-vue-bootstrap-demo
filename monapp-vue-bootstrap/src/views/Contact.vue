<template>
    <div>
      <div class="image">
      </div>
      <p></p> 
      <div class="row ml-4 mr-4">
        <div class="col-md-6">
            <base-input placeholder="name@example.com"></base-input>
        </div>
        <div class="col-md-6">
          <base-input placeholder="Disabled" disabled></base-input>
        </div>
      </div>
      <div class="row ml-4 mr-4">
          <div class="col-md-6">
              <base-input placeholder="Birthday" prepend-icon="ni ni-zoom-split-in"></base-input>
          </div>
          <div class="col-md-6">
            <base-input placeholder="Birthday" append-icon="ni ni-zoom-split-in"></base-input>
          </div>
        </div>
        <div class="row ml-4 mr-4">
          <div class="col-md-6">
              <base-input placeholder="Success" :valid="true"></base-input>
          </div>
          <div class="col-md-6">
            <base-input placeholder="Error input" error="Some error"></base-input>
          </div>
        </div>
    </div> 
</template>
<script>
export default {
  name: "contact",
}
</script>
<style>
.image {
  width: 100%;
  height: 200px;
  background-color:aqua;
  background-image: url('/img/mountains/montagne1.jpg');
  background-size: cover;
}
</style>
