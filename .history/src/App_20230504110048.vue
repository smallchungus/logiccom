<template>

<header>
  <h1>Voice Provisioning</h1>
</header>

  <form>
    <label for="partner">Select a partner:</label>
    <select id="partner" name="partner">
      <option value="Sprout">Sprout</option>
      <option value="option2">Option 2</option>
    </select>

    <label for="accountNum">Account Number:</label>
    <input type="text" id="accountNum" name="accountNum">

    <label for="firstName">First Name:</label>
    <input type="text" id="firstName" name="firstName">

    <label for="lastName">Last Name:</label>
    <input type="text" id="lastName" name="lastName">

    <label for="address">Address:</label>
    <input type="text" id="address" name="address">

    <label for="city">City:</label>
    <input type="text" id="city" name="city">

    <label for="state">State:</label>
    <input type="text" id="state" name="state">

    <label for="zip">Zip:</label>
    <input type="text" id="zip" name="zip">

    <label for="contactPhone">Contact Phone:</label>
    <input type="text" id="contactPhone" name="contactPhone">

    <label for="contactEmail">Contact Email:</label>
    <input type="text" id="contactEmail" name="contactEmail">

    <label for="customerType">Customer Type:</label>
    <select id="customerType" name="customerType">
      <option value="Sprout"></option>
      <option value="option2">Option 2</option>
    </select>

    <label for="phoneToProv">Phone Number to Provision:</label>
    <input type="text" id="phoneToProv" name="phoneToProv">

    <label for="sipPassword">Sip Password:</label>
    <input type="text" id="sipPassword" name="sipPassword">

    <label for="ported">Ported</label>
    <select id="ported" name="ported">
      <option value=""></option>
      <option value="option2">Option 2</option>
    </select>

    <label>
      <input type="checkbox" >
      Bypass E911 
    </label>
    <p v-if="isChecked">I'm checked!</p>

    <button type="submit">Provision</button>
  </form>
</template>

<style>
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