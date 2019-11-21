---
layout: form
title: Fresh Drop Info
---
<form>
<legend>Your Info here</legend>
  <fieldset class="account-info">
    <label>
        Name<input type="text" name="name" placeholder="Full name" required autofocus>
    </label>
    <label>
        Email<input type="email" name="email" placeholder="domain@address.com" required>
    </label>
    <label class="choice">
        Can we use your name in the article?<input type="radio" name="choice" value="Yes" checked> Yes
        <input type="radio" name="choice" value="No"> No. 
    </label>
  </fieldset>
  <fieldset class="account-action">
    <input class="btn" type="submit" name="submit" value="Login">
    <label>
      <input type="checkbox" name="remember"> Stay signed in
    </label>
  </fieldset>
</form>
     