<template>
  <v-card id="card">
    <div id="profile_header">
      <img id="profile-pic" src="./assets/profilepic.jpg" alt="profile picture">
      <h1>Hayden Randall</h1>
      <h3>Associate Software Developer Engineer in Test</h3>
    </div>
    <div class="info">
      <img class="left_off_set" src="./assets/smartphone.png" alt="">
      <p class="left_off_set">(480)-625-6584</p>
    </div>
    <div class="info">
      <img class="left_off_set" src="./assets/mail1.png" alt="">
      <p class="left_off_set email">haydenjrandall@gmail.com</p>
    </div>
    <div id="call_to_action">
      <h3>Let's connect!</h3>
      <p>Seeking Software Development Opportunities.</p>
      <p>Let's collaborate on your next project. Reach out to discuss how I can contribute to your team.</p>
    </div>
    <div id="social_media">
      <a href="https://www.linkedin.com/in/hayden-randall-56a98a207/" target="_blank"><img src="./assets/linkedin1.png" alt="linkedin icon"></a>
      <a class="icon_space" href="https://github.com/hjrandall" target="_blank"><img src="./assets/github.png" alt="github icon"></a>
    </div>
  </v-card>
</template>

<style scoped>
#card{
  width: 600px;
  height: auto;
  margin-top: 20px;
  margin-bottom: 20px;
  box-shadow: 0 6px 6px rgba(0, 0, 0, 1);
  background: linear-gradient(to bottom,rgb(229, 216, 203), rgb(191, 168, 161)  );
  color: rgb(255, 255, 255);
}
#profile-pic {
  margin-top: 20px;
  width: 150px;
  height: 216px;
  border-radius: 20px;
}
#profile_header{
  display: flex;
  flex-flow: column nowrap;
  align-items: center;
}
#call_to_action{
  display: flex;
  justify-content: center;
  align-items: center;
  flex-flow: column nowrap;
  padding-left:30px;
  padding-right:30px;
  margin-top: 10px;
  text-align: center;
}
#social_media{
  display: flex;
  justify-content: center;
  margin-top: 30px;
}
.icon_space{
  margin-left: 30px;
}
.email{
  margin-top: -10px;
}
.info{
  display: flex;
  flex-flow: column ;
  align-items: center;
  margin-top: 10px;
}
.left_off_set {
  margin-left: 10px;
}
p{
  font-size: 20px;
}
h3{
  color: rgb(52, 35, 43);
}
@media(max-width:640px){
    #card{
      width: 90%;
      text-align: center;
    }
    #call_to_action{
      padding: 0;
    }
  }
</style>
