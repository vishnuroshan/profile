<div class="container col-xl-10 col-xxl-8 px-4 py-5">
<div class="row align-items-center g-lg-5 py-5">
      <div class="col-lg-7 text-center text-lg-start">
        <h1 class="display-4 fw-bold lh-1 mb-3">👋<br>I am Vishnu Roshan,</h1>
        <p class="col-lg-10 fs-4">I make fast, profitable & pleasant web experiences.</p>
      </div>
      <div class="col-md-10 mx-auto col-lg-5">
        <form class="p-4 p-md-5 border rounded-3 bg-light">
          <div class="form-floating mb-3">
            <input type="email" class="form-control" id="floatingInput" placeholder="name@example.com">
            <label for="floatingInput">Email address</label>
          </div>
          <div class="form-floating mb-3 h-25">
            <textarea rows="3" class="form-control h-25" id="messageInput" placeholder="Your message" />
            <label for="messageInput">Message</label>
          </div>
          
          <button class="w-100 btn btn-lg btn-primary" type="submit">Lets connect</button>
          <hr class="my-4">
          <small class="text-muted">I usually take 2 to 3 days to respond, milage may vary!</small>
        </form>
      </div>
    </div>
</div>
<div class="divider">
 <span class="bar_content">
     Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s
   </span>
   
</div>


<style>
  .divider {
  color: black;
  height: fit-content;
  min-height: 2rem;
  background-color: rgba(0, 0, 0, .1);
  border: solid rgba(0, 0, 0, .15);
  border-width: 1px 0;
  box-shadow: inset 0 .5em 1.5em rgba(0, 0, 0, .1), inset 0 .125em .5em rgba(0, 0, 0, .15);
}

.bar_content {
  justify-content: center;
  text-align: center;
  display: block; /* Important to give the content a width */
  width: 100%;
  transform: translateX(100%); /* Animation start out of the screen */
  /* Add the animation */
  animation: move 30s linear infinite /* infinite make reapeat the animation indefinitely */;
}
/* Create the animation */
@keyframes move {
  to { transform: translateX(-100%); }
}
</style>

