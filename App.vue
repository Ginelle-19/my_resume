<template>
  <div>
    <div id="header"></div>
    <div class="left"></div>
    <div class="content">
        <br><br>
        <h1>{{msg}}</h1><br>
        <h2>Andrew Ginelle P. Macapagal</h2>
        <h4>Bachelor of Science in Information and Technology</h4>
        <h4>Major in Web Development</h4><br>
        <hr />
        <br>
         <p class="head">About Me</p>
         <ul>
           <li>Address: 2829 Dubai St. Purok Saudi, Mabiga, Mabalacat City</li>
           <li>e-mail: andrew.macapagal19@gmail.com</li>
           <li>Phone #: 09981234567</li>
         </ul>
        <p class="head">Objectives</p>
        <ul>
            <li>To gain experience and apply my knowledge in my job.</li>
            <li>To help the company in achieving its goals.</li>
            <li>To enhance my skills.</li>
            <li>To learn more about my expertice and be familiarized with my job's needs.</li>
        </ul>
        <p class="head">Education</p>
        <ul>
            <li>Elementary: Dau Central Elementary School</li>
            <li>Junior High school: Holy Angel University</li>
            <li>Senior High school: Holy Angel University</li> 
            <li>College: Holy Angel University</li>  
        </ul>
        <p class="head">Skills</p>
        <ul>
            <li>Java</li>
            <li>Python</li>
            <li>JavaScript</li>
            <li>PHP</li>
            <li>SQL</li>
        </ul>
    </div>
    <div class="right"></div>
    <div id="footer"></div>
</div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'This is your VueJS resume!'
    }
  }
}
</script>

<style>
.head{
  font-weight: bold;
  margin-bottom: 20px;
}
* {
  max-width: 700px;
  margin: auto;
}

body {
    min-width: 500px;
}

div {
  border-radius: 5px;
}

#header {
  height: 40px;
  width: 100%;
  background-color: #0c3953;
  position: fixed;
  z-index: 1;
}

#title {
  margin-left: 3%;
}

#footer {
  height: 50px;
  width: 100%;
  background-color: #298fca;
  clear: both;
  position: absolute;
}

.left {
  height: 1000px;
  width: 45px;
  background-color: #055a8c;
  float: left;
  position: fixed;
}

.right {
  height: 1050px;
  width: 45px;
  background-color: #055a8c;
  float: right;
  position: inherit;
}

.content {
  display: inline-block;
  margin-top: 6px;
  margin-left: 55px;
  width: 75%;
  height: 1000px;
}

p,
li {
  font-family: 'Cormorant Garamond';
}
ul{
  margin-bottom: 20px;
}

.head {
  font-size: 20px;
}

#name {
  font-family: Sacramento;
  float: right;
  margin-top: 10px;
  margin-right: 4%;
}

@media only screen and (max-width: 430px) {
  .left,
  .right {
    display: none;
  }
  .content {
    width: 100%;
    margin-left: 10px;
  }
}
</style>
