---
layout: page
title: Contact
background_style: bg-info
background_image: url('assets/img/backgrounds/image-from-rawpixel-id-1199650-jpeg.jpg')
# Add a link to the the top menu
menus:
  header:
    title: Contact
    weight: 2

sections:
- type: paragraph.html
  section_id: more-to-come
  title: No HTML!
#  background_style: bg-info
#  text_style: text-left text-white
  actions:
   - title: Markdown is fun!
     class: btn-info
     url: '#'
  text: >-
---

<form accept-charset="UTF-8" action="https://formspree.io/xleppdrd" method="POST" target="_blank">
    <div class="form-group">
    <label for="email" required="required">Email address
        <input type="email" name="email">
    </label>
    </div>
    <div class="form-group">
    <label for="name">Name
        <input type="text" name="name" class="form-control" id="name" placeholder="Enter your name" required="required">
    </label>
    </div>
    <div class="form-group">
    <label for="message">Message:
        <textarea type="text" name="name" required="required"></textarea>
    </label>    
    </div>
    <button type="submit" class="btn btn-primary">Submit</button>
</form>