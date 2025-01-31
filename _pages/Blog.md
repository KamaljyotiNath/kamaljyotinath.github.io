---
layout: archive
title:  Blog
permalink: /Blog/
author_profile: true
---

  <style>
    body {
      font-family: Arial, sans-serif;
    }

    /* Popup Styling */
    .popup {
      display: none;
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      width: 80%;
      max-width: 900px;
      background-color: white;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
      padding: 20px;
      z-index: 1000;
      overflow: hidden;
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

    iframe {
      width: 100%;
      height: 400px;
      border: none;
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
      float: right;
      font-size: 20px;
      font-weight: bold;
      cursor: pointer;
      color: #aaa;
    }

    .close-btn:hover {
      color: black;
    }
  </style>

  <!-- Open Pop-up Button -->
  <button onclick="BOOKPOP_1()">Open Pop-up</button>

  <!-- Overlay -->
  <div id="overlay" class="overlay" onclick="closePopup()"></div>

  <!-- Pop-up -->
  <div id="popup" class="popup">
    <span class="close-btn" onclick="closePopup()">&times;</span>
    <h3>Embedded Content</h3>
    <iframe id="popupIframe" src="" frameborder="0" scrolling="yes"></iframe>
  </div>
  
  <script>
    function BOOKPOP_1() {
      document.getElementById('popup').style.display = 'block';
      document.getElementById('overlay').style.display = 'block';
      
      // Set the src for the iframe to load external content
      document.getElementById('popupIframe').src = 'https://books.google.co.in/books?id=WV9CEAAAQBAJ&lpg=PA101&lr&pg=PA101&output=embed';  // Example URL
    }

    function closePopup() {
      document.getElementById('popup').style.display = 'none';
      document.getElementById('overlay').style.display = 'none';
      
      // Clear the src to stop loading when the popup is closed
      document.getElementById('popupIframe').src = '';
    }
  </script>



<!--
<style>
body {
  background-color: #ededed;
  color: black;
}

.dark-mode {
  background-color: black;
  color: white;
}

iframe {
      width: 100%;
      height: 400px;
      border: none;
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



<script>
function myFunction() {
   var element = document.body;
   element.classList.toggle("dark-mode");
}
</script>

-->

