<template>
  <h1 id="header">Web Registration Form</h1>
</template>

<style scoped>
h1 {
  color: black;
  font-size: 40px;
  font-family: "Crimson Text", serif;
}
#header {
  padding: 10px;
  margin: 0px 30% 0px 30%;
  opacity: 0.75;
  background-color: white;
  border: 1px solid #466a46;
}
@media only screen and (max-width: 1024px) {
  #header {
    margin: 10%;
  }
}
@media only screen and (max-width: 400px) {
  #header {
    margin: 0%;
  }
}
@media only screen and (max-width: 375px) {
  #header {
    font-size: 20px;
    padding: 5px;
  }
}
</style>
