---
layout: archive
title:  Blog
permalink: /Blog/
author_profile: true
---

# Embedded Book with Zoomed Content

Click on the button below to view the zoomed book content:

<button onclick="BOOKPOP_1()">Open Book</button>

<div id="popup" style="display:none; position:fixed; top:50%; left:50%; transform:translate(-50%, -50%); background:white; padding:20px; box-shadow: 0 4px 8px rgba(0,0,0,0.2); width:80%; max-width:900px;">
  <span onclick="document.getElementById('popup').style.display='none';" style="float:right; font-size:20px; cursor:pointer;">&times;</span>
  <h3>Embedded Content</h3>
  <iframe src="https://books.google.com/books?id=WV9CEAAAQBAJ&lpg=PA101&lr&pg=PA101&output=embed" style="width:100%; height:400px; border:none;"></iframe>
</div>




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

