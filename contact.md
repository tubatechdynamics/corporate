---
layout: page
title: "Contact Us"
meta_title: "Contact Tuba Tech Dynamics Corporate"
meta_description: "Contact Tuba Tech Dynamics to learn more about supporting non-profits through technology or how we can collaborate to drive social impact."
permalink: /contact/
---

Ready to support non-profits with cutting-edge technology solutions or learn more about partnering with us? Reach out today!

<form action="https://formsubmit.co/info@tubatechdynamics.com" method="POST">
  <!-- Add a hidden field to redirect to a thank you page (optional) -->
  <input type="hidden" name="_next" value="{{ '/thank-you/' | relative_url }}">
  <!-- Protect from spam -->
  <input type="hidden" name="_captcha" value="false">

  <label for="name">Name:</label><br>
  <input type="text" id="name" name="name" required><br>

  <label for="email">Email:</label><br>
  <input type="email" id="email" name="email" required><br>

  <label for="organization">Organization:</label><br>
  <input type="text" id="organization" name="organization"><br>

  <label for="message">Message:</label><br>
  <textarea id="message" name="message" rows="6" required></textarea><br>

  <button type="submit">Send Message</button>
</form>
