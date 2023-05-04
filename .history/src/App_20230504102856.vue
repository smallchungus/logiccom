<script setup lang="ts">

</script>
<template>
  <div>
    <label for="partner">Last Name:</label>
    <input type="text" id="partner">

    <label for="accountNum">Last Name:</label>
    <input type="text" id="accountNum">

    <label for="firstName">First Name:</label>
    <input type="text" id="firstName" >

    <label for="lastName">Last Name:</label>
    <input type="text" id="lastName">

    <label for="address">Last Name:</label>
    <input type="text" id="address">

    <label for="city">Last Name:</label>
    <input type="text" id="city">

    <label for="state">Last Name:</label>
    <input type="text" id="state">

    <label for="zip">Last Name:</label>
    <input type="text" id="zip">

    <label for="contactPhone">Last Name:</label>
    <input type="text" id="contactPhone">

    <label for="contactEmail">Last Name:</label>
    <input type="text" id="contactEmail">

    <label for="customerType">Last Name:</label>
    <input type="text" id="customerType">

    <label for="phoneToProv">Last Name:</label>
    <input type="text" id="phoneToProv">

    <label for="sipPassword">Last Name:</label>
    <input type="text" id="sipPassword">

    <label for="ported">Last Name:</label>
    <input type="text" id="ported">

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
