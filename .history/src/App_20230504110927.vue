<template>

<header>
  <h1>Voice Provisioning</h1>
</header>

<form>
      <div class="form-group">
        <label for="partner">Select a partner:</label>
        <select id="partner" name="partner">
          <option value="Sprout">Sprout</option>
          <option value="option2">Option 2</option>
        </select>
      </div>

      <div class="form-group">
        <input type="text" id="accountNum" name="accountNum" placeholder="Account Number">
      </div>

      <div class="form-group">
        <input type="text" id="firstName" name="firstName" placeholder="First Name">
      </div>

      <div class="form-group">
        <input type="text" id="lastName" name="lastName" placeholder="Last name">
      </div>

      <div class="form-group">
        <input type="text" id="address" name="address" placeholder="Address">
      </div>

      <div class="form-group">
        <input type="text" id="city" name="city" placeholder="City">
      </div>

      <div class="form-group">
        <input type="text" id="state" name="state" placeholder="State">
      </div>

      <div class="form-group">
        <input type="text" id="zip" name="zip" placeholder="Enter zip code">
      </div>

      <div class="form-group">
        <label for="contactPhone">Contact Phone:</label>
        <input type="text" id="contactPhone" name="contactPhone" placeholder="Enter contact phone number">
      </div>

      <div class="form-group">
        <label for="contactEmail">Contact Email:</label>
        <input type="text" id="contactEmail" name="contactEmail" placeholder="Enter contact email">
      </div>

      <div class="form-group">
        <label for="customerType">Customer Type:</label>
        <select id="customerType" name="customerType">
          <option value="Sprout">Sprout</option>
          <option value="option2">Option 2</option>
        </select>
      </div>

      <div class="form-group">
        <label for="phoneToProv">Phone Number to Provision:</label>
        <input type="text" id="phoneToProv" name="phoneToProv" placeholder="Enter phone number to provision">
      </div>

      <div class="form-group">
        <label for="sipPassword">Sip Password:</label>
        <input type="text" id="sipPassword" name="sipPassword" placeholder="Enter SIP password">
      </div>


    <label for="ported">Ported</label>
    <select id="ported" name="ported">
      <option value=""></option>
      <option value="option2">Option 2</option>
    </select>

    <label>
      <input type="checkbox" >
      Bypass E911 Address Automation
    </label>

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