<template>
  <div class="properties">
    <section>
      <h3>List of Properties</h3>
      <button>View All Properties</button>
    </section>
    <hr />

    <div class="top">
      <PropertyCard :imgUrl="'images/card1.png'" />
      <PropertyCard :imgUrl="'images/card2.png'" />
      <PropertyCard :imgUrl="'images/card3.png'" />
      <PropertyCard :imgUrl="'images/card4.png'" />
      <PropertyCard :imgUrl="'images/card5.png'" />
      <PropertyCard :imgUrl="'images/card6.png'" />
    </div>
  </div>

  <div class="button">
    <button class="first">First</button>
    <button class="num">1</button>
    <button class="active">2</button>
    <button class="num">3</button>
    <button class="next">Next</button>
  </div>
</template>

<script>
import PropertyCard from "./PropertyCard.vue";
export default {
  name: "Properties",
  components: { PropertyCard },
};
</script>

<style scoped>
.properties {
  padding: 93px 120px;
}

section {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

section h3 {
  font-weight: 800;
  font-size: 36px;
  text-transform: capitalize;
  color: #18191f;
}

.properties hr {
  width: 84px;
  height: 0px;
  border: 3px solid #f4511e;
}

.properties button {
  width: 200px;
  height: 65px;
  background: #f4511e;
  color: #ffffff;
  border-radius: 8px;
  box-shadow: 0px 20px 13px rgba(248, 90, 71, 0.035),
    0px 8.14815px 6.51852px rgba(248, 90, 71, 0.0274815),
    0px 1.85185px 3.14815px rgba(248, 90, 71, 0.0168519);
  border: none;
}

.top {
  margin-top: 50px;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 30px;
}

.button {
  display: flex;
  flex-direction: row;
  margin-top: 20px;
  margin-bottom: 20px;
  justify-content: center;
}

.button button{
   border: none;
}

button:hover{
   cursor: pointer;
}

.button .first {
  width: 50px;
  height: 50px;
  background: #f3f3f3;
  font-weight: 700;
  font-size: 14px;
  line-height: 24px;
  text-align: center;
  letter-spacing: 0.1px;
  color: #bdbdbd;
  border-top-left-radius: 10px;
  border-bottom-left-radius: 10px;
   box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.1);
}

.button .num {
  width: 30px;
  height: 50px;
  background: #f3f3f3;
  color: #f4511e;
  border: 1.5px solid #E8E8E8;
  font-weight: 700;
  font-size: 14px;
  line-height: 24px;
  text-align: center;
  letter-spacing: 0.1px;
}

.button .active {
  width: 30px;
  height: 50px;
  background: #f4511e;
  font-style: normal;
  font-weight: 700;
  font-size: 16px;
  line-height: 24px;
  text-align: center;
  letter-spacing: 0.1px;
  color: #ffffff;
}

.button .next{
   width: 50px;
  height: 50px;
  background: #f3f3f3;
  font-weight: 700;
  font-size: 14px;
  line-height: 24px;
  text-align: center;
  letter-spacing: 0.1px;
  color: #f4511e;
  border-top-right-radius: 10px;
  border-bottom-right-radius: 10px;
}
</style>
