---
# An instance of the Contact widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  form:
    provider: formspree
    formspree:
      id: https://formspree.io/f/xbjpqkal
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: True
  
design:
  columns: '2'
---
<form action="https://formspree.io/f/xbjpqkal" method="POST">
  <input type="text" name="name">
  <input type="email" name="_replyto">
  <input type="submit" value="Send">
</form>