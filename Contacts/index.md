---
layout: layouts/post.njk
title: Contact
templateClass: tmpl-post
eleventyNavigation:
  key: Contact
  order: 6
---

<div class="container">
  <div class="row p-3 pb-2 justify-content-center">
    <div class="col-12 text-center">
    <div class="col-12 col-lg-5 text-center">
      <form name="contact" method="POST" data-netlify="true">
        <label for="fname" class="form-label">Name:</label><br>
        <input type="text" id="name" name="name" class="form-control" required><br><br>
        <label for="email" class="form-label">Email:</label><br>
        <input type="email" id="email" name="email" class="form-control" required><br><br>
        <label for="message" class="form-label">Message:</label><br>
        <textarea id="message" name="message" rows="4" cols="50" class="form-control" required></textarea><br><br>
        <input type="submit" class="btn btn-outline-secondary">
      </form>
    </div>
  </div>
</div>