---
layout: single
title: "Contact"
permalink: /contact/
---

Have questions or want to get in touch? Fill out the form below to send me a message, or you can reach me directly at [admin@xinci.me](mailto:admin@xinci.me).

<style>
  form {
    max-width: 600px;
    margin: 0 auto;
    padding: 1rem;
    background-color: #f9f9f9;
    border: 1px solid #ddd;
    border-radius: 8px;
  }
  label {
    font-weight: bold;
    margin-top: 1rem;
    display: block;
    color: #333;
  }
  input, textarea {
    width: 100%;
    padding: 0.5rem;
    margin-top: 0.5rem;
    border: 1px solid #ccc;
    border-radius: 4px;
    font-size: 1rem;
  }
  button {
    margin-top: 1rem;
    padding: 0.75rem 1.5rem;
    background-color: #007acc;
    color: #fff;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 1rem;
  }
  button:hover {
    background-color: #005fa3;
  }
</style>

<form action="https://formspree.io/f/mzzbrzgn" method="POST">
  <label for="name">Your Name:</label>
  <input type="text" id="name" name="name" placeholder="Enter your name" required>

<label for="email">Your Email:</label>
<input type="email" id="email" name="email" placeholder="Enter your email" required>

<label for="message">Your Message:</label>
<textarea id="message" name="message" placeholder="Type your message here" required></textarea>

<button type="submit">Send</button>

</form>
