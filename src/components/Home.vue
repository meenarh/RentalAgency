<template>
  <div class="home">
    <nav>
      <img src="../assets/images/logo 1.png" alt="logo" />
      <ul class="nav-links">
        <a href="#">Home</a>
        <a href="#">Landlord</a>
        <a href="#">Tenant</a>
        <a href="#">Contact Us</a>
      </ul>
    </nav>
    <hr/>


    <section class="main">
      <h2>The most affortable place to stay in the san franciso bay area</h2>

      <div>
        <img src="../assets/images/Rectangle 1.png" />

        <div class="select">
          <select id="select1">
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
            <img src="../assets/images/search.png" alt="search" />
            <button type="search"></button>
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
  background-image: url("../assets/images/home-background.jpg"),
    linear-gradient(200.44deg, rgba(0, 0, 0, 0.0001) 16.41%, rgba(0, 0, 0, 0.51) 77.16%);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  height: 100vh;
  padding: 0px 120px;
}

nav {
  display: flex;
  padding: 20px;
  align-items: center;
  justify-content: space-between;
  text-align: center;
  gap: 10px;
  padding-left: 20px;
}

nav img {
  justify-content: left;
  margin-left: 10%;
}

.nav-links {
  display: flex;
  flex: 1 0 auto;
  gap: 10px;
  list-style: none;
  justify-content: center;
}
.nav-links a {
  text-decoration: none;
  padding: 0 20px;
  font-size: 20px;
  font-weight: 500;
  color: #fff;
}

.nav-links a:hover {
  text-decoration: underline;
  color: #fff;
}

hr{
  width: 80%;
  margin-left: 10%;
  top: 10px;
}

.main {
  display: flex;
  flex-direction: row;
  gap: 20px;
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
  font-family: 'Inter', sans-serif;
  font-style: normal;
  font-weight: 700;
  font-size: 52px;
  line-height: 70px;
  letter-spacing: -1px;
  text-transform: capitalize;
  color: #ffffff;
}

.select {
  background: #fff;
  height: 50px;
  width: 320px;
  border-radius: 10px;
  margin-left: 15px;
}

select {
  padding: 2px;
  height: 50px;
  width: 150px;
}

#select1 {
  border-right: 0px;
}

.select {
  display: flex;
  flex-direction: row;
  align-items: center;
  margin: 20px;
  padding: 20px;
}

button {
  position: relative;
  width: 50px;
  height: 52px;
  background: #23a6f0;
  border: 1px solid #e6e6e6;
  border-radius: 0px 5px 5px 0px;
  cursor: pointer;
}

.search img {
  position: absolute;
  z-index: 1;
  width: 20px;
  height: 20px;
  padding: 15px;
}
</style>
