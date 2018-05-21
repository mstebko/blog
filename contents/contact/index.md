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
<div class="col-1-3">
<div class="wrap-col">
<input name="name" id="name" placeholder="Enter name" required="required" type="text">
</div>
</div>
<div class="col-1-3">
<div class="wrap-col">
<input name="email" id="email" placeholder="Enter email" required="required" type="email">
</div>
</div>
<div class="col-1-3">
<div class="wrap-col">
<input name="subject" id="subject" placeholder="Subject" required="required" type="text">
</div>
</div>
</label>
<label class="row">
<div class="wrap-col">
<textarea name="message" id="message" class="form-control" rows="4" cols="25" required="required" placeholder="Message"></textarea>
</div>
</label>
<center><input class="sendButton" name="submitcontact" value="Submit" type="submit"></center>
</form>
</div>



