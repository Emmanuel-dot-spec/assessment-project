<template>
  <div class="app-form">
    <div class="logo-title">
      <div class="form-logo">
        <img src="../assets/app-form-logo.svg" alt="form-logo" />
      </div>
      <div>
        <h1 class="app-title">Application Form</h1>
      </div>
    </div>
    <div class="enclosure">
      <div class="upload-box">
        <div class="dots">
          <div>
            <img src="../assets/plus.svg" alt="plus-symbol" />
          </div>
          <div>
            <h1>Upload CV</h1>
          </div>
        </div>
        <div class="dots">
          <div>
            <img src="../assets/plus.svg" alt="plus-symbol" />
          </div>
          <div>
            <h1>Upload Photo</h1>
          </div>
        </div>
      </div>
      <div class="input-box">
        <div
          class="input-layer-one"
          style="display:flex; flex-direction:column"
        >
          <label for="">First Name</label>
          <input class="input-style" type="text" />
        </div>
        <div
          class="input-layer-one"
          style="display:flex; flex-direction:column"
        >
          <label for="">Last Name</label>
          <input class="input-style" type="text" />
        </div>
      </div>
      <div class="input-box">
        <div
          class="input-layer-one"
          style="display:flex; flex-direction:column"
        >
          <label for="">Email</label>
          <input class="input-style" type="text" />
        </div>
        <div
          class="input-layer-one"
          style="display:flex; flex-direction:column"
        >
          <label for="">Date of Birth</label>
          <input
            class="input-style"
            type="text"
            placeholder="dd/mm/yyyy"
            style="font-family: Lato;
font-style: italic;
font-weight: normal;
font-size: 10px;
line-height: 12px;
color: #CECECE;
padding-left:13px "
          />
        </div>
      </div>
      <div class="input-box">
        <div
          class="input-layer-one"
          style="display:flex; flex-direction:column"
        >
          <label for="">Address</label>
          <input class="input-style" type="text" />
        </div>
        <div
          class="input-layer-one"
          style="display:flex; flex-direction:column"
        >
          <label for="">University</label>
          <input class="input-style" type="text" />
        </div>
      </div>
      <div class="input-box">
        <div
          class="input-layer-one"
          style="display:flex; flex-direction:column"
        >
          <label for="">Course of Study</label>
          <input class="input-style" type="text" />
        </div>
        <div
          class="input-layer-one"
          style="display:flex; flex-direction:column"
        >
          <label for="">CGPA</label>
          <input class="input-style" type="text" />
        </div>
      </div>
      <div>
        <input class="sub-btn" type="submit" value="Submit" />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.logo-title {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 160px 0 40px;
}
.app-title {
  padding-top: 24px;
  font-family: Lato;
  font-style: italic;
  font-weight: 500;
  font-size: 24px;
  line-height: 29px;
  /* identical to box height */
  color: #2b3c4e;
}
.enclosure {
  width: 963px;
  height: 643px;
  background: #ffffff;
  box-shadow: 0px 5px 15px rgba(33, 31, 38, 0.05);
  border-radius: 8px;
  margin: auto;
  margin-bottom: 145px;
}
.upload-box {
  display: flex;
  align-items: center;
  justify-content: center;
  padding-top: 53px;
}
.dots {
  width: 211px;
  height: 49.97px;
  border: 1.5px dashed #2b3c4e;
  box-sizing: border-box;
  border-radius: 2.87205px;
  /*  */
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 0 16px 0;
}
.dots h1 {
  font-family: Avenir;
  font-size: 16px;
  line-height: 22px;
  /* identical to box height */
  color: #2b3c4e;
  padding: 0 13.97px 0;
}

.input-style {
  border: 1.5px solid #2b3c4e;
  box-sizing: border-box;
  border-radius: 4px;
  /*  */
  width: 379px;
  height: 48px;
}
.input-box {
  display: flex;
  align-items: center;
  justify-content: center;
}
input:focus {
  background: white;
  color: black;
}

label {
  font-family: Lato;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 17px;
  /* identical to box height */
  color: #2b3c4e;
  padding-bottom: 5px;
}
.input-layer-one {
  padding: 54px 36px 0;
}
.sub-btn {
  background: #7557d3;
  border-radius: 4px;
  width: 379px;
  height: 50px;
  /* text */
  font-family: Lato;
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 19px;
  /* identical to box height */
  color: #ffffff;
  /* position */
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 43px auto 39px;
}
@media screen and (max-width: 600px) {
  .upload-box {
    flex-direction: column;
  }
  .dots {
    margin: 20px 0;
  }
  .input-box {
    flex-direction: column;
  }
  .logo-title {
    padding: 120px 0 50px 470px;
  }
  .app-title {
    width: 190px;
    text-align: center;
  }
}
</style>
