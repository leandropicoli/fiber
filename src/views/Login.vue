<template>
  <div class="container">
    <div class="flex justify-center gap">
      <div class="login">
        <div class="margin flex">
          <h3>Fiber</h3>
        </div>

        <div class="margin flex">
          <h2>Create your Fiber account</h2>
        </div>

        <div class="margin flex column">
          <span class="label">Your Name</span>
          <input type="text" placeholder="John Doe" />
        </div>

        <div class="margin flex column">
          <span class="label">E-mail</span>
          <input type="email" placeholder="john@example.com" />
        </div>

        <div class="margin flex column">
          <span class="label">Password</span>
          <input type="password" placeholder="At least 8 characters" />
        </div>

        <div class="margin flex center">
          <input type="checkbox" />
          <p>
            By creating an account on Fiver, you agree to the
            <a href="#">Terms & Conditions.</a>
          </p>
        </div>

        <div class="margin">
          <button class="btn-submit">Create Fiber Account</button>
        </div>
      </div>

      <div class="content"></div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.container {
  margin: 100px 0;
}
.flex {
  display: flex;
}

.justify-space-around {
  justify-content: space-around;
}

.justify-center {
  justify-content: center;
}

.gap {
  gap: 30px;
}

.column {
  flex-direction: column;
}

.center {
  align-items: center;
}

.login {
  width: 30vw;
}

.margin {
  margin: 10px;
}

.content {
  width: 30vw;
  background-color: blueviolet;
}

.label {
  align-self: self-start;
  font-weight: 800;
}

.login input {
  margin: 5px 0;
  font-size: 17px;
  padding: 10px;
  height: 20px;
  border: 1px solid #80808066;
  border-radius: 5px;
}

.login p {
  margin-left: 5px;
  font-weight: 700;
}

input[type="checkbox"] {
  width: 15px;
}

login a {
  color: blueviolet;
}

.btn-submit {
  width: 100%;
  background-color: blueviolet;
  color: white;
  height: 50px;
  border: none;
  border-radius: 5px;
  font-size: 18px;
  font-weight: 700;
}
</style>