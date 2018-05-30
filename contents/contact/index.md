---
title: Code and stuff!
author: the-wintersmith
date: 2012-10-01 15:00
template: contact.jade
type: page
---

<h3 class="t-center" style="font-size: 30px;margin: 10px 0 30px">Contact Form
</h3>
<div id="contact_form">
<form name="form1" id="ff" method="post" action="contact.php">
<label class="row">
<div class="wrap-col">
<div class="form-heading">Name</div>
<input name="name" id="name" placeholder="Enter name" required="required" type="text">
</div>
<div class="wrap-col">
<div class="form-heading">Email</div>
<input name="email" id="email" placeholder="Enter email" required="required" type="email">
</div>
<div class="wrap-col">
<div class="form-heading">Subject</div>
<input name="subject" id="subject" placeholder="Subject" required="required" type="text">
</div>
</label>
<label class="row">
<div class="wrap-col">
<div class="form-heading">Message</div>
<textarea name="message" id="message" class="form-control" rows="4" cols="25" required="required" placeholder="Message"></textarea>
</div>
</label>
<center><input class="sendButton" name="submitcontact" value="Send" type="submit"></center>
</form>
</div>



