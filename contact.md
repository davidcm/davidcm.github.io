---
layout: layout
title: Contact
redirect_from: /support/
---

{{page.title}}
===

Use the form below to send a message or support request.

<form action="http://getsimpleform.com/messages?form_api_token=e6eae6975dc108c66d07db50a623c53c" method="post">
  <input type="hidden" name="redirect_to" value="http://www.david.cm/contact-thankyou" />
  <p>
    <label>Your name:</label>
    <input type="text" name="name" maxlength="30">
  </p>
  <p>
    <label>Your email:</label>
    <input type="email" name="email" maxlength="30" />
  </p>
  <p>
    <label>Product:</label>
    <input type="text" name="product" maxlength="30" />
  </p>
  <p>
    <label>Description:</label>
    <textarea name="message" cols="40" rows="6" maxlength="1500" wrap="soft"></textarea>
  </p>
  <p>
    <label>&nbsp;</label>
    <input type="submit" value="Send" />
  </p>
</form>

