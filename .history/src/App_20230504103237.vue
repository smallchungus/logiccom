<script setup lang="ts">
</script>
<template>
  <div>
    <label for="mySelect">Select an option:</label>
<select id="mySelect">
  <option value="option1">Option 1</option>
  <option value="option2">Option 2</option>
  <option value="option3">Option 3</option>
</select>

    <label for="accountNum">Account Number:</label>
    <input type="text" id="accountNum">

    <label for="firstName">First Name:</label>
    <input type="text" id="firstName" >

    <label for="lastName">Last Name:</label>
    <input type="text" id="lastName">

    <label for="address">Address:</label>
    <input type="text" id="address">

    <label for="city">City:</label>
    <input type="text" id="city">

    <label for="state">State:</label>
    <input type="text" id="state">

    <label for="zip">Zip:</label>
    <input type="text" id="zip">

    <label for="contactPhone">Contact Phone:</label>
    <input type="text" id="contactPhone">

    <label for="contactEmail">Contact Email:</label>
    <input type="text" id="contactEmail">

    <label for="customerType">Customer Type:</label>
    <input type="text" id="customerType">

    <label for="phoneToProv">Phone Number to Provision:</label>
    <input type="text" id="phoneToProv">

    <label for="sipPassword">Sip Password:</label>
    <input type="text" id="sipPassword">

    <label for="ported">Ported:</label>
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
