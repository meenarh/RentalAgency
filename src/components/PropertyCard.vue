<template>
  <div class="card">
    <div class="image">
      <img :src="imgUrl" alt="" />
    </div>
    <h3>2578 Folsom street, san francisco, CA, 94110</h3>
    <div class="info">
      <p>Private Room</p>
      <p>$1200/month</p>
    </div>
    <div class="icons">
      <span>
        <img src="../assets/images/bed.svg" alt="" />
        <p>4</p>
      </span>
      <span>
        <img src="../assets/images/Shower.svg" alt="" />
        <p>2</p>
      </span>
      <span>
        <img src="../assets/images/Size.svg" alt="" />
        <p>2</p>
      </span>
    </div>

    
  </div>
</template>

<script>
export default {
  name: "PropertyCard",
  props: {
    imgUrl: String,
  },
};
</script>

<style scoped>
.card {
  display: flex;
  flex-direction: column;
  max-width: 358px;
  width: 100%;
  max-height: 522px;
  height: 100%;
  background: #fff;
  border: 1px solid #979797;
  border-radius: 26.6166px;
  cursor: pointer;
}

.card:hover {
  box-shadow: 0px 34.0693px 36.1986px rgba(0, 0, 0, 0.133714);
}

.image {
  width: 100%;
  height: 50%;
  overflow: hidden;
}

.image img {
  width: 100%;
  object-fit: cover;
}

.card h3 {
  padding: 20px 46px 20px 27px;
  text-transform: capitalize;
  font-weight: 700;
  font-size: 23px;
}

.info p:nth-child(1) {
  font-family: "DM Sans", sans-serif;
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 23px;
  letter-spacing: -0.642075px;
  text-transform: capitalize;
  padding-left: 27px;
  color: #818181;
}

.info p:nth-child(2) {
  font-family: "DM Sans";
  font-style: normal;
  font-weight: 700;
  font-size: 25.552px;
  line-height: 33px;
  letter-spacing: -0.642075px;
  text-transform: capitalize;
  color: #f4511e;
  padding-left: 27px;
}

.icons {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}

.icons span {
  display: flex;
  flex-direction: row;
  align-items: center;
  margin-top: 33px;
  padding: 27px 44px 27px 45px;
}

.icons span p {
  margin-left: 2px;
  font-family: "DM Sans";
  font-style: normal;
  font-weight: 700;
  font-size: 18.0993px;
  line-height: 24px;
  letter-spacing: -0.454803px;
  color: #000000;
}

.icons span:nth-child(1) {
  border-top: 0.5px solid #818181;
  border-right: 0.5px solid #818181;
}

.icons span:nth-child(2) {
  border-top: 0.5px solid #818181;
  border-right: 0.5px solid #818181;
}

.icons span:nth-child(3) {
  border-top: 0.5px solid #818181;
}


</style>
