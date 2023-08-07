

<div class="hero min-h-screen bg-base-200">
  <div class="hero-content flex-col lg:flex-row">
    <div class="text-center lg:text-left">
      <h1 class="text-5xl font-bold">Login now!</h1>
      <p class="py-6">From timeless classics to modern masterpieces, find your next read at Book Nook. Sign in to explore, share, and enjoy the world of literature like never before.</p>
    </div>
    <div class="card flex-shrink-0 w-full max-w-sm shadow-2xl bg-base-100">
      <div class="card-body">
        <div class="form-control">
          <label class="label" for="email">
            <span class="label-text">Email</span>
          </label>
          <input id="email" type="text" placeholder="email" class="input input-bordered" />
        </div>
        <div class="form-control">
          <label class="label" for="password">
            <span class="label-text">Password</span>
          </label>
          <input id="password" type="text" placeholder="password" class="input input-bordered" />
          <!-- <a href="#" class="label-text-alt link link-hover m-1">Forgot password?</a> -->
        </div>
        <div class="form-control mt-6">
          <button class="btn btn-primary">Login</button>
        </div>
      </div>
    </div>
  </div>
</div>

<style>
    .hero {
        background-image: url('$lib/images/hero.jpg');
        background-size: cover;
        background-position: center center;
    }
</style>