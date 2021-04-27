<template>
<div>
  <div class="row">
  <div class="col-6 col-md-5">
    <img src="../assets/girl.png" align="center" href="https://dribbble.com/shots/10859087-The-girl-learns-the-space?utm_source=pinterest&utm_campaign=pinterest_shot&utm_content=The+girl+learns+the+space&utm_medium=Social_Share"/>
  </div>
    <div class="col-md-7 home-headers">
    <h1 style="font-weight: 800">Hi ! I'm Amelia Nimbus -</h1>
    <h2 style="font-weight: 600" align="center">WRITER</h2>
    <h6 align="center">I am a person who loves his job and cares a lot about the details. He cares very much about learning new things and improving my skills. For this purpose, I think it is necessary to benefit from the teaching of human relations.</h6>
    <a id="e-mail" > <b>E-Mail :</b> amelianimbus@hotmail.com</a>
    <a id="linkedin"> <b>LinkedIn :</b> @amelialimbus</a> <br />
    <button type="button" class="btn home-buttons" id="cv">Download CV</button>
    <button type="button" class="btn home-buttons" id="hire">Hire Me Now</button>
  </div>
  </div>
  <div class="row">
  <div class="col-2"></div>
  <div class="col-2"></div>
  <div class="col-2 home-features"> <button type="button" class="btn home-buttons" id="feature"><i class="fa fa-home" style="color: #1b1717"></i>WRITER <br><a style="color:#1b1717; opacity:0.7"> improving my skills</a></button></div>
  <div class="col-2 home-features"><button type="button" class="btn home-buttons" id="feature"><i class="fa fa-home" style="color: #00255e;"></i>READER <br><a style="color:#1b1717; opacity:0.7"> improving my skills</a></button></div>
  <div class="col-2 home-features"><button type="button" class="btn home-buttons" id="feature"><i class="fa fa-home" style="color: #169dc2;"></i>FREELANCER<br><a style="color:#1b1717; opacity:0.7"> improving my skills</a></button></div>
  <div class="col-2"></div>
  </div>
</div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>
