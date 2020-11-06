<template>
  <Layout>
  <div class="flex-container">
  <div class="flex-container1">
  <div class="flex-item-left1"><g-link to="/">INSTAGRAM</g-link></div>
  <div class="flex-item-left2"><g-link to="/">SOUNDCLOUD</g-link></div></div>
  <div class="flex-container2">
  <div class="flex-item-right1"><g-link to="/">NEWSLETTER</g-link></div>
  <div class="flex-item-right2">COPYRIGHT 2020</div></div>
</div>
   
  </Layout>
</template>



<style scoped>
@media (max-width: 48em) {
* {
  box-sizing: border-box;
}

.flex-container {
  display: flex;
  flex-direction: row;
  font-size: 1em;
  text-align: center;
  margin-top:8em;
  margin-left:5vw;
  margin-right: 5vw;
  background-color: yellow;
  border-radius: 25px;
}

.flex-container1 {
  display: flex;
  flex-direction: row;
  text-align: center;
}

.flex-container2 {
  display: flex;
  flex-direction: row;
  text-align: center;
}

.flex-item-left1 {
  background-color: none;
  padding-TOP: .67em;
  padding-bottom:.125em;
  flex: 10%;
}

.flex-item-left2 {
  background-color: none;
  padding-TOP: .67em;
  padding-bottom:.125em;
  flex: 10%;
}

.flex-item-right1 {
  background-color: none;
  padding-TOP: .125em;
  padding-bottom:.67em;
  flex: 10%;
}

.flex-item-right2 {
  background-color: none;
  padding-top: .125em;
  padding-bottom:.67em;
  flex: 10%;
}}

@media (min-width: 48em) {
* {
  box-sizing: border-box;
}

.flex-container {
  display: flex;
  flex-direction: row;
  font-size: 1em;
  text-align: center;
  margin-top:8em;
  margin-left:8vw;
  margin-right: 8vw;
  background-color: yellow;
  border-radius: 25px;
}

.flex-container1 {
  display: flex;
  flex-direction: row;
  text-align: center;
  margin-left: 12vw;
  background-color: none;
}

.flex-container2 {
  display: flex;
  flex-direction: row;
  text-align: center;
  margin-right: 6vw;
  background-color: none;

}

.flex-item-left1 {
  background-color: none;
  padding-top: .67em;
  padding-bottom:.125em;
  padding-left: .67em;
  padding-right: .67em;
  margin-right: .67vw;
  margin-left: .67vw;
  flex: 10%;
}

.flex-item-left2 {
  background-color: none;
  padding: .67em;
  margin-right: .67vw;
  margin-left: .67vw;
  flex: 20%;
}

.flex-item-right1 {
  background-color: none;
  padding:.67em;
  margin-right: .67vw;
  margin-left: .67vw;
  flex: 10%;
}

.flex-item-right2 {
  background-color:none;
  padding:.67em;
  margin-right: .67vw;
  margin-left: .67vw;
  flex: 20%;
}}

@media (min-width: 70em) {
* {
  box-sizing: border-box;
}

.flex-container {
  display: flex;
  flex-direction: row;
  font-size: 1.34em;
  text-align: center;
  align-items: center;
  margin-top:8em;
  margin-left:8vw;
  margin-right: 8vw;
  padding-left: 8vw;
  padding-right: 8vw;
  background-color: yellow;
  border-radius: 25px;

}

.flex-container1 {
  display: flex;
  flex-direction: row;
  text-align: center;
  margin-left: 2vw;
}

.flex-container2 {
  display: flex;
  flex-direction: row;
  text-align: center;
}

.flex-item-left1 {
  background-color: darkblue;
  padding-top: .67em;
  padding-bottom:.125em;
  flex: 10%;
}

.flex-item-left2 {
  background-color: none;
  padding: .67em;
  flex: 10%;
}

.flex-item-right1 {
  background-color: none;
  padding:.67em;
  flex: 10%;
}

.flex-item-right2 {
  background-color:none;
  padding:.67em;
  flex: 10%;
  width: 12em;
}}

/* Responsive layout - makes a one column-layout instead of two-column layout */
@media (max-width: 800px) {
  .flex-container {
    flex-direction: column;
  }
}
</style>