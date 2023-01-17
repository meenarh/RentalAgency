<template>
  <div class="cost">
    <h3>Minimum living cost takes care of everything</h3>
    <hr />
    <div class="body">
      <div class="image">
        <img src="../assets/images/costImg.png" alt="" />
      </div>

      <div class="right">
        <!-- the icons -->
        <div class="icon">
          <span>
            <img src="../assets/images/dollarIcon.svg" alt="" />
          </span>
          <p>Pay as Little as possible!</p>
        </div>
        <div class="icon">
          <span>
            <img src="../assets/images/dollarIcon.svg" alt="" />
          </span>
          <p>Enjoy wisdom of community!</p>
        </div>
        <div class="icon">
          <span>
            <img src="../assets/images/dollarIcon.svg" alt="" />
          </span>
          <p>Let's somebody else take care of Landlord!</p>
        </div>
        <div class="icon">
          <span>
            <img src="../assets/images/dollarIcon.svg" alt="" />
          </span>
          <p>Enjoy peaceful Environment!</p>
        </div>
        <div class="icon">
          <span>
            <img src="../assets/images/dollarIcon.svg" alt="" />
          </span>
          <p>
            Stay Safe! <br />
            Save Money!
          </p>
        </div>
        <div class="icon">
          <span>
            <img src="../assets/images/dollarIcon.svg" alt="" />
          </span>
          <p>
            Pay for what <br />
            you use !
          </p>
        </div>
        <!-- the icons -->
        <!-- the icons -->
        <!-- the icons -->
        <!-- the icons -->
        <!-- the icons -->
        <!-- the icons -->
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Cost",
};
</script>

<style scoped>
.cost {
  background-color: #f5f5f5;
  padding: 93px 120px;
  display: flex;
  flex-direction: column;
}
.cost h3 {
  font-weight: 800;
  font-size: 36px;
  color: #000000;
  line-height: 64px;
}
.cost hr {
  width: 385px;
  height: 0px;
  border: 3px solid #f4511e;
}

.cost .body {
  display: flex;
  flex-direction: row;
  /* justify-content: space-between; */
  align-items: center;
  gap: 65px;
  margin-top: 50px;
}

.cost .body .image {
  max-width: 100%;
  display: flex;
  flex-direction: start;
  box-shadow: 5px 24px 53px rgba(0, 0, 0, 0.25);
  border-radius: 50px 0px;
}
.cost .body .image img {
  width: 387px;
  height: 521px;
  background-color: transparent;
}
.cost .body .right {
  display: grid;
  gap: 50px;
  grid-template-columns: repeat(3, 1fr);
}

.cost .body .right .icon {
  display: flex;
  flex-direction: column;
  gap: 21px;
}
.cost .body .right .icon span {
  width: 77px;
  height: 77px;
  display: flex;
  align-items: center;
  justify-content: center;
  background: #ffffff;
  box-shadow: 0px 12px 19px rgba(0, 0, 0, 0.15);
  border-radius: 10px;
}
.cost .body .right .icon p {
  font-weight: 600;
  font-size: 26px;
  line-height: 35px;
}
</style>
