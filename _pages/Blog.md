---
layout: archive
title:  Blog
permalink: /Blog/
author_profile: true
---

<style>
body {
  background-color: #ededed;
  color: black;
}
/* Popup Styling */
popup {
      visibility: hidden;
      opacity: 0;
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      width: 80%;
      max-width: 500px;
      background-color: white;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
      padding: 20px;
      z-index: 1000;
      transition: opacity 0.3s ease-in-out, visibility 0.3s ease-in-out;
    }

    /* Overlay Styling */
    .overlay {
      display: none;
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.5);
      z-index: 999;
    }

    /* Button Styling */
    button {
      margin: 10px;
      padding: 10px 15px;
      font-size: 16px;
      cursor: pointer;
      background-color: #007bff;
      color: white;
      border: none;
      border-radius: 5px;
    }

    button:hover {
      background-color: #0056b3;
    }

    /* Close Button */
    .close-btn {
      font-size: 20px;
      font-weight: bold;
      cursor: pointer;
      color: #aaa;
    }

    .close-btn:hover {
      color: black;
    }

    /* Show popup */
    .popup.show {
      visibility: visible;
      opacity: 1;
    }

.dark-mode {
  background-color: black;
  color: white;
}
summary {
      font-weight: bold;
      font-size: 22px;
      cursor: pointer;
      color: #007BFF;
    }

  summary:hover {
      color: #0056b3;
  }

  details[open] summary {
      color: #FF5733;
    padding-bottom:-10;
    }
p{
  margin:0;
  padding:0;
}  
</style>

<button onclick="myFunction()">Toggle dark mode</button>

<details>
  <summary>Click to expand!</summary>
  
  under construction
</details>

<button onclick="showPopup()">Open Popup</button>

  <!-- Overlay -->
  <div id="overlay" class="overlay" onclick="hidePopup()"></div>

  <!-- Popup -->
  <div id="popup" class="popup">
    <span class="close-btn" onclick="hidePopup()">&times;</span>
    <h3>Hello World</h3>
    <div>
    <iframe frameborder="0" scrolling="no" style="border:0px" src="https://books.google.co.in/books?id=WV9CEAAAQBAJ&lpg=PA101&lr&pg=PA101&output=embed" width=500 height=500></iframe>
  </div>
  </div>

  <script>
    function showPopup() {
      document.getElementById('popup').classList.add('show');
      document.getElementById('overlay').style.display = 'block';
    }

    function hidePopup() {
      document.getElementById('popup').classList.remove('show');
      document.getElementById('overlay').style.display = 'none';
    }
  </script>

<script>
function myFunction() {
   var element = document.body;
   element.classList.toggle("dark-mode");
}
</script>



