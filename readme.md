<!DOCTYPE html>
<html>

<body>
<div class="form" id="loginform">
    <h1> Login </h1>
    <form novalidate>
        <p class="email">
            <label for="email">Email login <span>*</span>
            </label>
            <input class="input" required type="email" id="email" name="email" pattern="@"/>
          <span class="validation error"> Please enter a valid email</span>
          <span class="validation req"> This field is required</span>
        </p>
        <p class="password">
            <label for="password">Password <span>*</span></label>
            <input class="input" required type="password" id="password" name="password" />
          <span class="validation req"> This field is required</span>
        </p>
      <p class="remember">
        <input class="checkbox" type="checkbox" id="remember"/>
        <label for="remember"> Remember me</label>
        
      </p>
      <p class="login">
        <input type="submit" value="Login" />
      </p>
    </form>
</div>

</body>
</html>
