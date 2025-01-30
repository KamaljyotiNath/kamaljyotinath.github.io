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
    .book-popup {
      visibility: hidden;
      opacity: 0;
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
      transition: opacity 0.3s ease-in-out, visibility 0.3s ease-in-out;
    }

    /* Overlay Styling */
    .popup-overlay {
      display: none;
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.5);
      z-index: 999;
    }

    /* Scrollable container */
    .iframe-container {
      width: 100%;
      height: 80vh; /* Adjust to fit the viewport */
      overflow: auto;
      border: 1px solid #ccc;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    /* Zoom effect inside pop-up */
    .iframe-wrapper {
      transform: scale(1.2); /* Adjust zoom level */
      transform-origin: center center;
      margin: auto;
    }

    iframe {
      width: 100%;  /* Make iframe take up full width of its container */
      height: 100%; /* Adjust to container's height */
      border: none;
    }

    /* Button Styling */
    .open-btn {
      margin: 10px;
      padding: 10px 15px;
      font-size: 16px;
      cursor: pointer;
      background-color: #007bff;
      color: white;
      border: none;
      border-radius: 5px;
    }

    .open-btn:hover {
      background-color: #0056b3;
    }

    /* Close Button */
    .close-btn {
      float: right;
      font-size: 20px;
      font-weight: bold;
      cursor: pointer;
      color: #cc1d1d;
    }

    .close-btn:hover {
      color: black;
    }

    /* Show popup */
    .book-popup.show {
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

<!-- Open Pop-up Buttons -->
  <button class="open-btn" onclick="showBookPopup('bookPopup1', 'https://books.google.co.in/books?id=WV9CEAAAQBAJ&lpg=PA101&lr&pg=PA101&output=embed')">
    Open Book 1
  </button>

  <!-- Overlay -->
  <div id="popupOverlay" class="popup-overlay" onclick="hideBookPopup()"></div>

  <!-- Pop-up 1 -->
  <div id="bookPopup1" class="book-popup">
    <span class="close-btn" onclick="hideBookPopup()">&times;</span>
    <div class="iframe-container">
      <div class="iframe-wrapper">
        <iframe id="bookFrame1" frameborder="0" scrolling="no" style="border:0px" width=500 height=500> ffghhg</iframe>
      </div>
    </div>
  </div>

  <script>
    function showBookPopup(popupId, bookUrl) {
      document.getElementById(popupId).classList.add('show');
      document.getElementById('popupOverlay').style.display = 'block';
      
      // Load iframe dynamically
      document.querySelector(`#${popupId} iframe`).src = bookUrl;
    }

    function hideBookPopup() {
      document.querySelectorAll('.book-popup').forEach(popup => {
        popup.classList.remove('show');
      });
      document.getElementById('popupOverlay').style.display = 'none';
    }
  </script>

<script>
function myFunction() {
   var element = document.body;
   element.classList.toggle("dark-mode");
}
</script>



