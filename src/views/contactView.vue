<template>
  <div class="holder">
    <div class="heading text-center">
    <h1>Looking Forward To Hear From You!</h1>
  </div>

  <div class="form container mt-5">
    <div class="text">
      <p>Required fields are marked with *</p>
    </div>
    <form action="https://formspree.io/f/mayzkeqz" method="POST">
      <div class="names row">
        <div class="mb-3 col-6">
          <label for="exampleFormControlInput1" class="form-label"
            >First Name *</label
          >
          <input
            name="name"
            class="form-control"
            id="exampleFormControlInput1"
            placeholder="Enzo"
            required
            oninvalid="this.setCustomValidity('Please insert your first name')"
            oninput="this.setCustomValidity('')"
          />
        </div>
        <div class="mb-3 col-6">
          <label for="exampleFormControlInput1" class="form-label"
            >Last Name *</label
          >
          <input
            name="name"
            class="form-control"
            id="exampleFormControlInput1"
            placeholder="Ferrari"
            required
            oninvalid="this.setCustomValidity('Please insert your last name')"
            oninput="this.setCustomValidity('')"
          />
        </div>
      </div>
      <div class="mb-3">
        <label for="exampleFormControlInput1" class="form-label"
          >Email address *</label
        >
        <input
          type="email"
          class="form-control"
          id="exampleFormControlInput1"
          placeholder="Enzo@ferrari.com"
          required
          oninvalid="this.setCustomValidity('Please insert your email address')"
          oninput="this.setCustomValidity('')"
        />
      </div>
      <div class="mb-3">
        <label for="exampleFormControlTextarea1" class="form-label"
          >Leave a Message *</label
        >
        <textarea
          class="form-control"
          id="exampleFormControlTextarea1"
          rows="6"
          required
          oninvalid="this.setCustomValidity('Please insert your message')"
          oninput="this.setCustomValidity('')"
        ></textarea>
      </div>
      <div class="formButtons">
        <div class="submit">
          <button type="submit">Send</button>
        </div>
        <div class="reset mb-3">
          <button type="reset">Reset</button>
        </div>
      </div>
    </form>
  </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.holder{
  min-height: 100vh;
  background: rgb(28, 29, 32);

}
.heading {
  margin-bottom: 20px;
  color:#4e851e;
  filter: drop-shadow(4px 9px 5px black);
  transform: translateY(30px)


}

.form {
  height: 100% !important;
  width: 50%;
  margin-bottom: 20px;
}
.text {
  display: flex;
}
input,
textarea {
  color: #eeebdd !important;
  background: radial-gradient(circle at 10% 20%, rgb(69, 86, 102) 0%, rgb(34, 34, 34) 90%);

  border-radius: 20px;
}

::placeholder {
  color: #eeebdd;
}
.formButtons {
  display: flex;
  justify-content: center;
}
.submit,
.reset {
}

button {
  color: #eeebdd;
  background:rgb(34,34,34);
  width: 100px;
  border: 0px;
  border-radius: 20px;
  padding: 5px 8px 5px 8px;
  box-shadow: 0 0 0 0 transparent;
  -webkit-transition: all 0.2s ease-in;
  -moz-transition: all 0.2s ease-in;
  transition: all 0.2s ease-in;
}

button:hover {
  color: #eeebdd;
  background: #8ACD50;
  box-shadow: 0 0 30px 5px #8ACD50;
  -webkit-transition: all 0.2s ease-out;
  -moz-transition: all 0.2s ease-out;
  transition: all 0.2s ease-out;
}

@media only screen and (max-width: 350px) {
  .form{
    width:100% !important;
  }
 

  input {
    width: 100%;
  }
  .formButtons {
   display: flex;
   justify-content: center;
  }
  button {
    margin: 8px
  }
  
  button:hover {
    color: #eeebdd;
    background: #1ce278;
    box-shadow: 0 0 30px 5px #1ce278;
    -webkit-transition: all 0.2s ease-out;
    -moz-transition: all 0.2s ease-out;
    transition: all 0.2s ease-out;
  }
 
}
</style>