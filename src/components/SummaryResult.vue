<template>
  <div class="grid-container">
    <div class="grid-child-purple">
      <h3>Your Result</h3>

      <span class="dot">
        <h1>76</h1>
        <span>out of 100</span>
      </span>
      <h2>Great</h2>
      <p class="p-des">loreal ipsum is done here and you can see</p>
    </div>

    <div class="grid-child-green">
      <h2 style="text-align: left; padding-left: 15px">Summary</h2>
      <div class="react-bac">
        <img src="../icons/icon-reaction.svg" alt="My reaction SVG" />Reaction
        <span style="text-align: right; margin-left: 115px">80/100</span>
      </div>
      <div
        class="react-bac"
        style="background-color: hsl(39, 52%, 94%); color: hsl(39, 100%, 56%)"
      >
        <img src="../icons/icon-memory.svg" alt="memory icon" />Memory
        <span style="text-align: right; margin-left: 45%">92/100</span>
      </div>
      <div
        class="react-bac"
        style="background-color: hsl(163, 47%, 91%); color: hsl(166, 100%, 37%)"
      >
        <img src="../icons/icon-verbal.svg" alt="verbal icon" />Verbal
        <span style="text-align: right; margin-left: 48%">61/100</span>
      </div>
      <div
        class="react-bac"
        style="background-color: hsl(235, 51%, 90%); color: hsl(234, 85%, 45%)"
      >
        <img src="../icons/icon-visual.svg" alt="visual icon" />Visual
        <span style="text-align: right; margin-left: 50%">72/100</span>
      </div>
      <button>Continue</button>
    </div>
  </div>
  <!-- <div> -->
  <!-- <body>
      <div class="result-section">
        <h1>Your Result</h1>
      </div>
      <div class="summary-section">
        <h1>Result</h1>
      </div>
    </body> -->
  <!-- </div> -->
</template>

<script>

export default {
  // eslint-disable-next-line
  name: "SummaryResult",

};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Hanken+Grotesk:wght@200&display=swap");
.grid-container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-gap: 20px;
}
.grid-child-purple {
  background-color: hsl(234, 85%, 45%);
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);

  border-radius: 10px;

  color: white;
  width: 320px;
  height: 410px;
  margin-left: 300px;
  margin-top: 40px;
}
.grid-child-green {
  background-color: hsl(0, 0%, 100%);
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);

  border-radius: 10px;

  color: black;
  width: 320px;
  height: 410px;
  margin-top: 40px;
}
.dot {
  height: 40%;
  width: 50%;
  background-color: hsl(234, 85%, 45%);
  /* background-color: red; */
  border-radius: 50%;
  display: inline-block;
  margin-top: 20px;
  background-image:linear-gradient(
    /* to top left, */
    rgb(51, 22, 132) ,hsla(241, 74%, 45%, 0) 

    );
    border-color:hsl(234, 84%, 39%)
}
.p-des {
  color: white;
}
.react-bac {
  color: hsl(0, 100%, 67%);
  background-color: hsla(0, 100%, 90%, 0.3);
  padding: 15px;
  margin: 10px;
  box-shadow: 0 2px 8px rgba(236, 233, 233, 0.26);
  border-radius: 10px;
  text-align: left;
  font-family: "Hanken Grotesk", sans-serif;
}

button {
  background-color: hsl(224, 30%, 27%);
  color: white;
  margin: 10px;
  padding: 10px;
  width: 250px;
  border-radius: 20px;
}
img {
  margin-right: 15px;
}
* {
  box-sizing: border-box;
  font-family: "Hanken Grotesk", sans-serif;
}

html {
  font-family: "Hanken Grotesk", sans-serif;
}
</style>
