<template>
  <div class="container-fluid">
    <section class="row equipment-site">
      <div class="col-12  fs-3 text-center text-white p-4">
        <p class="p-0">Golden Rule</p>
        <p class="p-0">Equipment</p>
      </div>
      <div class="col-12 mt-5 d-flex justify-content-evenly align-items-center text-light p-4 green-section">
        <p>Home</p>
        <p>Machinery</p>
        <p>Dismantled Machinery</p>
        <p>Attachments</p>
        <p>Trucks and Trailers</p>
        <p>Parts</p>
        <p>Financing</p>
        <p>Contact Us</p>
        <p>Store</p>
      </div>
      <div class="col-12 text-white fs-1 ms-5 pt-0 ">
        <p>TIRED of Paying Exhorbitant Prices</p>
        <p>for Forestry Parts?</p>
        <button class="btn contact-button">CONTACT US</button>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  setup() {
    return {

    }
  }
}
</script>

<style scoped lang="scss">
.equipment-site {
  background-image: url("https://plus.unsplash.com/premium_photo-1661962956543-82fb286018e6?w=800&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NXx8Zm9yZXN0cnklMjBlcXVpcG1lbnR8ZW58MHx8MHx8fDA%3D");
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
  height: 580px;
}

.green-section {
  background-color: #145A32;
  height: 85px;
}

.contact-button {
  background-color: #F1C40F;
  border-radius: 0;
  color: gray;
}
</style>
