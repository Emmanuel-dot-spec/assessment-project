<template>
  <div class="admin-login">
    <div class="enclosure">
      <div class="central-wrapper">
        <div class="logo-title">
          <div>
            <img
              style="display:flex; align-items:center; justify-content:center; margin:auto;"
              src="../assets/enyata-logo-white.svg"
              alt=""
            />
          </div>
          <div>
            <h1 class="heading-text" style="text-align:center">
              Admin Log In
            </h1>
          </div>
        </div>
        <div class="input-box">
          <div
            class="input-layer-one"
            style="display:flex; flex-direction:column"
          >
            <label for="">Email Address</label>
            <input class="input-style" type="text" />
          </div>
        </div>
        <div class="input-box">
          <div
            class="input-layer-one"
            style="display:flex; flex-direction:column"
          >
            <label for="">Password</label>
            <input class="input-style" type="text" />
          </div>
        </div>
        <div>
          <input class="sub-btn" type="submit" value="Sign In" />
        </div>
      </div>
      <div>
        <img class="laptop" src="../assets/laptop.svg" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scooped>
.enclosure {
  width: 100%;
  height: 928px;
  background: #7557d3;
  display: flex;
  align-items: center;
  justify-content: flex-end;
}
.heading-text {
  font-family: Lato;
  font-style: italic;
  font-weight: 500;
  font-size: 24px;
  line-height: 29px;
  /* identical to box height */
  color: #ffffff;
  padding-top: 24px;
}
.input-box {
  display: flex;
  align-items: center;
  justify-content: center;
}
.input-style {
  background: #7557d3;
  border: 1.5px solid #ffffff;
  box-sizing: border-box;
  border-radius: 4px;

  /*  */
  width: 379px;
  height: 48px;
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

  color: #ffffff;
  padding-bottom: 5px;
}
.input-layer-one {
  padding: 40px 36px 0;
}
.sub-btn {
  background: #ffffff;
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
  color: #7557d3;
  /* position */
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 43px auto 39px;
}
@media screen and (max-width: 600px) {
  .enclosure {
    display: flex;
    flex-direction: column;
  }
}
</style>
