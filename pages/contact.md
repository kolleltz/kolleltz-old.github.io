---
layout: page
title: "Contact"
meta_title: "Contact and use our contact form"
subheadline: "Wufoo-powered contact forms"
teaser: "Get in touch with me? Use the contact form."
permalink: "/contact/"
---
If you need a fabulous contact form for your website, I suggest you use [Wufoo][1]. You can use three forms for free, you get no spam and if you get more than 100 entries you have to pay.


 [1]: http://www.wufoo.com/
 
 
{% include contact-form.html %}
 
<form method="POST" action="https://formspree.io/dan.kerchner@gmail.com">
  <input type="email" name="email" placeholder="Your email">
  <textarea name="message" placeholder="Test Message"></textarea>
  <button type="submit">Send Test</button>
</form>
