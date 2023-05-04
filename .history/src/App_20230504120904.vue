<style src="./styles.css"></style>


<template>


<form>
  <header>
    <h1>Voice Provisioning</h1>
  </header>
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

    <div class="form-row">
      <div class="form-group">
        <input type="text" id="firstName" name="firstName" placeholder="First Name" class="inline">
      </div>

      <div class="form-group">
        <input type="text" id="lastName" name="lastName" placeholder="Last Name" class="inline">
      </div>
    </div>

    <div class="form-row">
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
        <input type="text" id="zip" name="zip" placeholder="Zip">
      </div>
    </div>

    <div class="form-row">
      <div class="form-group">
        <input type="text" id="contactPhone" name="contactPhone" placeholder="Contact Phone">
      </div>

      <div class="form-group">
        <input type="text" id="contactEmail" name="contactEmail" placeholder="Contact Email">
      </div>
    </div>
      <div class="form-group">
        <label for="customerType">Customer Type:</label>
        <select id="customerType" name="customerType">
          <option value="Sprout">Sprout</option>
          <option value="option2">Option 2</option>
        </select>
      </div>

      <div class="form-group">
        <input type="text" id="phoneToProv" name="phoneToProv" placeholder="Phone number to provision">
      </div>

      <div class="form-group">
        <input type="password" id="sipPassword" name="sipPassword" placeholder="SIP password">
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
