---
title: "Get in touch"
date: 2019-11-19T15:31:23Z
draft: false
---

<form action="/thankyou" method="post" name="Contact" data-netlify="true" netlify-honeypot="bot-field" netlify>

  <p vissibility: hidden>
    <label>Dont fill this in if you are human</label> 
    <input name="bot-field"> 
  </p>
  <label for="fname">First Name</label>
  <br>
  <input type="text" id="fname" name="firstname" placeholder="Your first name. . .">
  <br>
  <br>
  <label for="lname">Last Name</label>
  <br>
  <input type="text" id="lname" name="lastname" placeholder="Your last name. . .">
  <br>
  <br>
  <label for="email">EMail Address</label>
  <br>
  <input type="text" id="email" name="email" placeholder="Your EMail. . ." style="width: 30vw">
  <br>
  <br>
  <label for="message">Message</label>
  <br>
  <textarea id="message" name="message" placeholder="Write something interesting . . ." style="height: 20vw; width: 70vw"></textarea>
  <br>
  <br>
  <div data-netlify-recaptcha></div>
  <br>
  <br>
  <input type="submit" value="Submit" style="height: 10vw; width: 15vw; cursor: pointer; font-size: 2vw;">
  
</form>