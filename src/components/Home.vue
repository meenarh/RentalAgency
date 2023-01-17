<template>
  <div class="home">
    <nav>
      <img src="../assets/images/logo 1.png" alt="logo" />
      <ul class="nav-links">
        <li>Home</li>
        <li>Landlord</li>
        <li>Tenant</li>
        <li>Contact Us</li>
      </ul>
    </nav>

    <section class="main">
      <h2>The most affortable place to stay in the san franciso bay area</h2>

      <div>
        <img src="../assets/images/Rectangle 1.png" />

        <div class="select">
          <select>
            <option>All Types</option>
            <option>Apartment</option>
            <option>House</option>
            <option>Condo</option>
            <option>Studio</option>
          </select>
          <select>
            <option>Neighbourhood</option>
            <option>Apartment</option>
            <option>House</option>
            <option>Condo</option>
            <option>Studio</option>
          </select>
          <div class="search">
            <input type="search" />
            <font-awesome-icon
              icon="fa-sharp fa-solid fa-magnifying-glass"
            />
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>

<style scoped>
.home {
  background-image: url("../assets/images/home-background.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  height: 100vh;
}
nav {
  display: flex;
  justify-content: space-between;
  padding: 20px;
}
.nav-links {
  display: flex;
  list-style: none;
}
.nav-links li {
  padding: 0 20px;
  font-size: 20px;
  font-weight: 500;
  color: #fff;
}

.main {
  display: flex;
  flex-direction: row;
  gap: 10px;
  align-items: center;
  margin: 20px;
  padding: 20px;
}

.main img {
  width: 400px;
  height: 400px;
  border-radius: 10px;
  margin-bottom: 10px;
  background: none;
}

.main h2 {
  font-size: 50px;
  color: #fff;
  font-weight: 700;
  line-height: 70px;
  letter-spacing: -1px;
  text-transform: capitalize;
  top: 30px;
}

.select {
  background: #fff;
  height: 55px;
  width: 350px;
  border-radius: 10px;
}

select {
  height: 50px;
  width: 120px;
}

.select {
  display: flex;
  flex-direction: row;
  align-items: center;
  margin: 20px;
  padding: 20px;
}

input {
  position: relative;
  width: 50px;
  height: 51px;
  background: #23a6f0;
  border: 1px solid #e6e6e6;
  border-radius: 0px 5px 5px 0px;
  color: white;
}

.search img {
  position: absolute;
  width: 20px;
  height: 20px;
  background: black;
}
</style>
