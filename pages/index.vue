<template>
  <div id="index">
    <div>
      <img id="logo" src="#"/>
    </div>

    <div id="dropdown">
      <div class="drop">
        <v-select :items="items" outlined label="items" class="drops"></v-select>
      </div>

      <div class="drop">
        <v-select :items="items" outlined label="items" class="drops"></v-select>
      </div>
    </div>


    <div id="form">
      <div id="box-form">
      <div class="forms">
        <p>Search</p>
        <v-input>What do you search</v-input>
      </div>

      <div class="forms">
        <p>Search by Tag</p>
        <v-input>Choice between tag</v-input>
      </div>
    </div>

    <div class="forms">
      <p>Most Used Tag</p>
      <v-input disabled></v-input>
    </div>
      <v-btn>Search</v-btn>
    </div>

    <div id="new">



    </div>


  </div>
</template>

<script>

export default {

}
</script>
