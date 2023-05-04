<script setup lang="ts">

</script>

<template>
  <div>

    <label for="partner">Last Name:</label>
    <input type="text" id="partner">


    <label for="firstName">First Name:</label>
    <input type="text" id="firstName" >

    <label for="lastName">Last Name:</label>
    <input type="text" id="lastName">

    <label for="lastName">Last Name:</label>
    <input type="text" id="lastName">

    <button>Submit</button>
  </div>
</template>



@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
