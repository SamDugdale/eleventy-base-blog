---
layout: layouts/base.njk
title: Contact
templateClass: tmpl-post
eleventyNavigation:
  key: Contact
  order: 6
---

<h1>{{ title }}</h1>

<div class="container" id= "contactf">
  <div class="row p-3 pb-2 justify-content-center">
    <div class="col-12 text-center">
    <div class="col-12 col-lg-5 text-center">
      <form name="contact" method="POST" data-netlify="true">
        <label for="fname" class="form-label">First Name:</label><br>
        <input type="text" id="fname" name="First Name" class="form-control" required><br><br>
        <label for="sname" class="form-label">Surname:</label><br>
        <input type="text" id="sname" name="Surname" class="form-control" required><br><br>
        <label for="email" class="form-label">Email:</label><br>
        <input type="email" id="email" name="email" class="form-control" required><br><br>
        <label for="message" class="form-label">Message:</label><br>
        <textarea id="message" name="message" rows="4" cols="50" class="form-control" required></textarea><br><br>
        <input type="submit" class="btn btn-outline-secondary">
      </form>
    </div>
  </div>
</div>