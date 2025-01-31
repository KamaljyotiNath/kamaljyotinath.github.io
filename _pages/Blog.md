---
layout: archive
title:  Blog
permalink: /Blog/
author_profile: true
---
# Click the button to open a pop-up

<button onclick="BOOKPOP_1()">Open Pop-up</button>

<div id="popup" style="display:none;">
  <span onclick="closePopup()" style="cursor:pointer;">&times;</span>
  <iframe id="popupIframe" src="https://books.google.co.in/books?id=WV9CEAAAQBAJ&lpg=PA101&lr&pg=PA101&output=embed" width="100%" height="400px"></iframe>
</div>

<script>
  function BOOKPOP_1() {
    document.getElementById('popup').style.display = 'block';
  }

  function closePopup() {
    document.getElementById('popup').style.display = 'none';
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

