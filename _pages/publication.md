---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<style>
body {
  background-color: #ededed;
  color: black;
}

.dark-mode {
  background-color: black;
  color: white;
}


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
      height: 100%;
      overflow: auto;
      border: 1px solid #ccc;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    /* Zoom effect inside pop-up */
    .iframe-wrapper {
      transform: scale(1.5); /* Increase content size */
      transform-origin: center center;
      margin: auto;
      max-width: fit-content;
    }

    iframe {
      width: 800px; 
      height: 100%;
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
      color: #aaa;
    }

    .close-btn:hover {
      color: black;
    }

    /* Show popup */
    .book-popup.show {
      visibility: visible;
      opacity: 1;
    }  
  

.button {
  background-color: #008CBA;
  color: white;
  border: none;
  /* padding: 12px 20px; */
  text-align: center;
  text-decoration: none;
  /* display: inline-block; */
  font-size: 16px;
  margin: 2px 2px;
  /* ursor: pointer; */
}
button:hover {
  background-color: #4682B4;
  border: none;
  color: white;
}  

.class_1 {
  background-color: #94e5ff;
  border: none;
  border-radius: 6px;
  color: black;
  margin: 3px 3px;
  font-size: 16px;
  min-width: 60px;
  min-height: 20px;} /* #94e5ff,  Blue  #008CBA*/

  details[open] summary {
      color: #FF5733;
    padding-bottom:-10;
    }

.class_dark_button {
  border-radius: 50%;
  border: none;
  margin: 0px 0px;
  background-color: none;
    }
  
p.p_class_1 {
  margin: 5pt;
  padding: 5pt;
  line-height: 1.5;
  font-size: 18px;
  color: blue;
  text-align: justify;
  /*font-family: 'Courier New', monospace;*/
}
p.p_main {
  margin: 0pt;
  padding: 0pt;
  font-size: 18px;
  text-align: justify;
  /*font-family: 'Courier New', monospace;*/
  /*font-family: Verdana;*/
}




</style>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<button onclick="myFunction()" class="class_dark_button">
<i class="fa fa-adjust" style="font-size:24px"></i>
</button>
<script>
function myFunction() {
   var element = document.body;
   element.classList.toggle("dark-mode");
}
</script>


<!-- --------------- --------------- --------------- --------------- --------------- --------------- --------------- --------------- --------------- --------------- -->

<a id="top"></a>
<a target="_blank" rel="noopener noreferrer" href = "https://scholar.google.co.in/citations?user=U9Vf1IwAAAAJ&hl=en"> Google Scholar profile </a>

<!-- * *Contributed equally -->
<body onkeydown="ESCclose(event)"></body>
<!-- PRIPRINTS -->
<a id="Preprints"></a>
### Preprints
<ol  reversed="reversed">
  <p style='text-align: justify;'>
    <li> 
      <p class="p_main">  <b>  Kamaljyoti Nath</b>, Varun Kumar, Daniel J. Smith, George Em Karniadakis (2024) <a target="_blank" rel="noopener noreferrer" href = "https://arxiv.org/abs/2412.11967">  A Digital twin for Diesel Engines: Operator-infused PINNs with Transfer Learning for Engine Health Monitoring </a>
      </p>
    </li> 
  </p> 
</ol>

<!-- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- -->
<!-- BOOK CHAPTET -->
<a id="Book chapter"></a>
### Book Chapters
<ol reversed="reversed"> <p style='text-align: justify;'>
<li> 
  <p class="p_main">
    <b>  Kamaljyoti Nath</b>, Anjan Dutta, Budhaditya Hazra (2021). <a target="_blank" rel="noopener noreferrer" href="https://www.taylorfrancis.com/chapters/edit/10.1201/9781003194613-8/stochastic-finite-element-method-kamaljyoti-nath-anjan-dutta-budhaditya-hazra?context=ubx&refId=07d53908-1c18-4fad-9beb-be78b05e9096">  Stochastic Finite Element Method </a>. In: Farsangi, E.N., Noori, M., Gardoni, P., Takewaki, I., Varum, H., & Bogdanovic, A. (Eds.) <a href ="https://doi.org/10.1201/9781003194613">  <i> Reliability-Based Analysis and Design of Structures and Infrastructure (1st ed.) </i> </a> (pp. 101-116). CRC Press. </p>

<button class="open-btn" onclick="showBookPopup('bookPopup1', 'https://books.google.co.in/books?id=WV9CEAAAQBAJ&lpg=PA101&lr&pg=PA101&output=embed')">
    Read on Google Book
  </button>
  
 <!-- Overlay -->
  <div id="popupOverlay" class="popup-overlay" onclick="hideBookPopup()"></div>

  <!-- Pop-up 1 -->
  <div id="bookPopup1" class="book-popup">
    <span class="close-btn" onclick="hideBookPopup()">&times;</span>
    <div class="iframe-container">
      <div class="iframe-wrapper">
        <iframe id="bookFrame1" frameborder="0" scrolling="no" style="border:0px"></iframe>
      </div>
    </div>
  </div>



<!--
<button onclick="document.getElementById('CITE_Nath_2021_SFEM_Chapter').style.display='block'" class="class_1"> Cite </button>
<div id="CITE_Nath_2021_SFEM_Chapter" style="display: none; position: fixed; top: 20%; right: 2%; width: 40%; height: auto; background-color: rgba(0, 0, 0, 0.7);">
    <div style="position: absolute; background-color: white; margin: 10px; padding: 10px; width: 100%; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
      <span onclick="document.getElementById('CITE_Nath_2021_SFEM_Chapter').style.display='none'" style="color: #aaa; font-size: 28px; font-weight: bold; float: right;"> </span>
      <h3 style="font-size: 18px;" style="color:blue;">Cite Article</h3>
      <pre style="font-size: 12px;" style="color:blue;">
@incollection{Nath_2021_SFEM_Chapter,
  author={Nath, Kamaljyoti and Dutta, Anjan and Hazra, Budhaditya},
  title={Stochastic Finite Element Method},
  booktitle={Reliability-Based Analysis and Design of Structures and Infrastructure},
  pages={101--116},
  year={2021},
  publisher={CRC Press}
}
      </pre>
    </div>
  </div>  -->
  
<!-- /p --> </li>
</p>
</ol>

<!-- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- -->
<a id="Journal"></a>
### Journals
<ol reversed="reversed" start="9"> <p style='text-align: justify;'>
<!-- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- -->
<li>
<p class="p_main"> Sathesh Mariappan, <b>Kamaljyoti Nath</b>, George Em Karniadakis (2024), Learning thermoacoustic interactions in combustors using a physics-informed neural network. <i> Engineering Applications of Artificial Intelligence </i>, 138, 109388. </p>
  <div style="display: flex; gap: 10px; margin-bottom: 20px;">
  <button onclick="document.getElementById('Abstract_Mariappan_2024_PINN').style.display='block'; document.getElementById('OVERLAY_Abstract_Mariappan_2024_PINN').style.display='block'" class="class_1"> 
    Abstract
  </button>
  <a target="_blank" rel="noopener noreferrer" href = "https://doi.org/10.1016/j.engappai.2024.109388" class="class_1"> <button class="class_1">Journal</button></a>
  <a target="_blank" rel="noopener noreferrer" href="https://doi.org/10.48550/arXiv.2401.00061" class="class_1"><button class="class_1"> arXiv </button></a>
  <button onclick="document.getElementById('CITE_Mariappan_2024_PINN').style.display='block'; document.getElementById('OVERLAY_CITE_Mariappan_2024_PINN').style.display='block'" class="class_1"> Cite  </button>
  </div>
</li>  
<!-- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- -->  
<li>
<p class="p_main">
  Felipe de Castro Teixeira Carvalho, <b>Kamaljyoti Nath</b>, Alberto Luiz Serpa, George Em Karniadakis (2024), Learning characteristic parameters and dynamics of centrifugal pumps under multiphase flow using physics-informed neural networks. <i> Engineering Applications of Artificial Intelligence </i>, 138, 109378. </p>
  <div style="display: flex; gap: 10px; margin-bottom: 20px;">
    <button onclick="document.getElementById('Abstract_Felipe_2024_PINN').style.display='block'; document.getElementById('OVERLAY_Abstract_Felipe_2024_PINN').style.display='block'" class="class_1">  
      Abstract
    </button>
    <a target="_blank" rel="noopener noreferrer" href = "https://doi.org/10.1016/j.engappai.2024.109378" class="class_1"> <button class="class_1"> Journal </button> </a>
    <a target="_blank" rel="noopener noreferrer" href="https://doi.org/10.48550/arXiv.2310.03001" class="class_1"><button class="class_1"> arXiv </button> </a>
    <button onclick="document.getElementById('CITE_Felipe_2024_PINN').style.display='block'; document.getElementById('OVERLAY_CITE_Felipe_2024_PINN').style.display='block'" class="class_1">
    Cite
  </button>
 </div>
</li> 
<!-- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- -->  
<li>
<p class="p_main"> 
  Lizuo Liu, <b>Kamaljyoti Nath</b>, Wei Cai (2024), A Causality-DeepONet for Causal Responses of Linear Dynamical Systems. <i>Communications in Computational Physics</i>, 35 (5), 1194-1228.</p>
  <div style="display: flex; gap: 10px; margin-bottom: 20px;">
  <button onclick="document.getElementById('Abstract_Liu_2022_Causality').style.display='block'; document.getElementById('OVERLAY_Abstract_Liu_2022_Causality').style.display='block'" class="class_1">
      Abstract
    </button>  
  <a target="_blank" rel="noopener noreferrer" href="https://doi.org/10.4208/cicp.OA-2023-0078" class="class_1"><button  class="class_1">Journal</button></a> 
  <a target="_blank" rel="noopener noreferrer" href="https://www.researchgate.net/publication/381733362_A_Causality-DeepONet_for_Causal_Responses_of_Linear_Dynamical_Systems" class="class_1"> <button class="class_1"> ResearchGate </button>  </a>   
  <a target="_blank" rel="noopener noreferrer" href="https://doi.org/10.48550/arXiv.2209.08397" class="class_1"> <button  class="class_1">arXiv</button> </a> 
  <button onclick="document.getElementById('CITE_Liu_2022_Causality').style.display='block'; document.getElementById('OVERLAY_CITE_Liu_2022_Causality').style.display='block'" class="class_1">
    Cite
  </button>
  </div>
</li> 
<!-- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- -->
  
<li>
<p class="p_main">
    <b>Kamaljyoti Nath</b>*, Xuhui Meng*, Daniel J Smith, George Em Karniadakis (2023) Physics-informed neural networks for predicting gas flow dynamics and unknown parameters in diesel engines. <i>Scientific Reports</i>, 13, 13683. </p>
  <div style="display: flex; gap: 10px; margin-bottom: 20px;">
  <button onclick="document.getElementById('Abstract_Nath_2023').style.display='block'; document.getElementById('OVERLAY_Abstract_Nath_2023').style.display='block'" class="class_1">
      Abstract
    </button>  
  <a target="_blank" rel="noopener noreferrer" href = "https://doi.org/10.1038/s41598-023-39989-4" class="class_1"> <button class="class_1">Journal-Open Access</button></a>
 <button onclick="document.getElementById('CITE_Nath_2023').style.display='block'; document.getElementById('OVERLAY_CITE_Nath_2023').style.display='block'" class="class_1">
    Cite
  </button> <span style="font-size: 16px;" > *Contributed equally  </span>
  </div>
</li>
<!-- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- -->
<li>
<p class="p_main">
<b>Kamaljyoti Nath</b>, Anjan Dutta, Budhaditya Hazra (2022) An adaptive scheme for random field discretization using KL expansion. <i>Engineering with Computers</i>, 38, 2937–2954.</p>
<div style="display: flex; gap: 10px; margin-bottom: 20px;">
  <button onclick="document.getElementById('Abstract_Nath_2022_Ad_KL').style.display='block'; document.getElementById('OVERLAY_Abstract_Nath_2022_Ad_KL').style.display='block'" class="class_1">
      Abstract
    </button>  
  <a target="_blank" rel="noopener noreferrer" href = "https://doi.org/10.1007/s00366-021-01326-6" class="class_1"> <button class="class_1">Journal</button></a>
  <button onclick="document.getElementById('CITE_Nath_2022_Ad_KL').style.display='block'; document.getElementById('OVERLAY_CITE_Nath_2022_Ad_KL').style.display='block'" class="class_1">
    Cite
  </button>
  </div>
</li>

<!-- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- -->
<li>
<p class="p_main">
    <b>Kamaljyoti Nath</b>, Anjan Dutta, Budhaditya Hazra (2021) Iterative Polynomial Dimensional Decomposition approach towards solution of structural mechanics problems with material randomness. <i>Probabilistic Engineering Mechanics</i>, 66, 103159. </p>
  <div style="display: flex; gap: 10px; margin-bottom: 20px;">
  <button onclick="document.getElementById('Abstract_Nath_2021_IPDD').style.display='block'; document.getElementById('OVERLAY_Abstract_Nath_2021_IPDD').style.display='block'" class="class_1">
      Abstract
    </button>  
  <a target="_blank" rel="noopener noreferrer" href = "https://doi.org/10.1016/j.probengmech.2021.103159" class="class_1"> <button class="class_1">Journal</button></a>
  <button onclick="document.getElementById('CITE_Nath_2021_IPDD').style.display='block'; document.getElementById('OVERLAY_CITE_Nath_2021_IPDD').style.display='block'" class="class_1">
    Cite
  </button>
  </div>
</li>
<!-- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- -->

<li>
  <p class="p_main">
    <b>Kamaljyoti Nath</b>, Anjan Dutta, Budhaditya Hazra (2020) Long duration response evaluation of linear structural system with random system properties using time dependent polynomial chaos. <i>Journal of Computational Physics</i>, 418, 109596. </p>
<div style="display: flex; gap: 10px; margin-bottom: 20px;">
  <button onclick="document.getElementById('Abstract_Nath_2020_TDgPC').style.display='block'; document.getElementById('OVERLAY_Abstract_Nath_2020_TDgPC').style.display='block'" class="class_1">
      Abstract
    </button>  
  <a target="_blank" rel="noopener noreferrer" href = "https://doi.org/10.1016/j.jcp.2020.109596" class="class_1"> <button class="class_1">Journal</button></a>
  <button onclick="document.getElementById('CITE_Nath_2020_TDgPC').style.display='block'; document.getElementById('OVERLAY_CITE_Nath_2020_TDgPC').style.display='block'" class="class_1">
    Cite
  </button>
  </div>
</li>
<!-- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- -->
<li>
<p class="p_main"> <b>Kamaljyoti Nath</b>, Anjan Dutta, Budhaditya Hazra (2019) An iterative polynomial chaos approach toward stochastic elastostatic structural analysis with non‐Gaussian randomness.  <i>International Journal for Numerical Methods in Engineering</i>, 119(11), 1126-1160. </p>
<div style="display: flex; gap: 10px; margin-bottom: 20px;">
  <button onclick="document.getElementById('Abstract_Nath_2019_IPC_Non_Gauss').style.display='block'; document.getElementById('OVERLAY_Abstract_Nath_2019_IPC_Non_Gauss').style.display='block'" class="class_1">
      Abstract
    </button>  
  <a target="_blank" rel="noopener noreferrer" href = "https://doi.org/10.1002/nme.6086" class="class_1"> <button class="class_1">Journal</button></a>
  <button onclick="document.getElementById('CITE_Nath_2019_IPC_Non_Gauss').style.display='block'; document.getElementById('OVERLAY_CITE_Nath_2019_IPC_Non_Gauss').style.display='block'" class="class_1">
    Cite
  </button>
  </div>
</li>
<!-- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- -->
<li> 
  <p class="p_main">
    <b>Kamaljyoti Nath</b>, Anjan Dutta, Budhaditya Hazra (2019) An iterative polynomial chaos approach for solution of structural mechanics problem with Gaussian material property. <i> Journal of Computational Physics </i>, 390, 425-451. </p>
<div style="display: flex; gap: 10px; margin-bottom: 20px;">
  <button onclick="document.getElementById('Abstract_Nath_2019_IPC_Gauss').style.display='block'; document.getElementById('OVERLAY_Abstract_Nath_2019_IPC_Gauss').style.display='block'" class="class_1">
      Abstract
    </button>  
  <a target="_blank" rel="noopener noreferrer" href = "https://doi.org/10.1016/j.jcp.2019.04.014" class="class_1"> <button class="class_1">Journal</button></a>
  <button onclick="document.getElementById('CITE_Nath_2019_IPC_Gauss').style.display='block'; document.getElementById('OVERLAY_CITE_Nath_2019_IPC_Gauss').style.display='block'" class="class_1">
    Cite
  </button>
  </div>
</li>
<!-- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- -->
</p></ol>

<!-- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- -->
### Conference
<ol reversed="reversed"> <p style='text-align: justify;'>
<li> <p class="p_main">  Amartya Dutta, <b> Kamaljyoti Nath</b> (2020). <a target="_blank" rel="noopener noreferrer" href ="https://doi.org/10.1007/978-981-16-3690-5_31"> Learning via Long Short-Term Memory (LSTM) Network for Predicting Strains in Railway Bridge Members Under Train Induced Vibration.</a> 2nd International Conference on Data Science, Machine Learning and Applications (ICDSMLA) 2020 (held virtually), Pune, India. In: Kumar A., Senatore S., Gunjan V.K. (eds) Lecture Notes in Electrical Engineering, vol 783 (pp. 351-361). Springer, Singapore. https://doi.org/10.1007/978-981-16-3690-5_31  </p> </li>
</p>
  
</ol> 
<div style="display: flex; gap: 10px; margin-bottom: 20px;">
<a href="#top" class="class_1"> <button class="class_1"> Back to top </button> </a> 
<a href="#Book chapter" class="class_1"> <button class="class_1"> Back to Book chapter </button> </a> 
<a href="#Journal" class="class_1"> <button class="class_1"> Back to Journals </button>  </a>
</div>




{% include_relative publication_cite.md %}
{% include_relative publication_abstract.md %}

<!-- -------- --------- -------- -------- -------- -------- -------- -------- -------- -------- -------- -------- -------- -------- --------------------------------- -------- -------- -------- -------- -------- -------- -->
<!-- ------------ Overlay ---------- -->
<!-- Overlay -->
<div id="OVERLAY_Abstract_Mariappan_2024_PINN" class="overlay" style="display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.5); z-index: 999;" onclick="document.getElementById('Abstract_Mariappan_2024_PINN').style.display='none'; document.getElementById('OVERLAY_Abstract_Mariappan_2024_PINN').style.display='none'">
</div>
<div id="OVERLAY_Abstract_Felipe_2024_PINN" class="overlay" style="display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.5); z-index: 999;" onclick="document.getElementById('Abstract_Felipe_2024_PINN').style.display='none'; document.getElementById('OVERLAY_Abstract_Felipe_2024_PINN').style.display='none'">
</div>
<div id="OVERLAY_Abstract_Liu_2022_Causality" class="overlay" style="display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.5); z-index: 999;" onclick="document.getElementById('Abstract_Liu_2022_Causality').style.display='none'; document.getElementById('OVERLAY_Abstract_Liu_2022_Causality').style.display='none'">
</div>
<div id="OVERLAY_Abstract_Nath_2023" class="overlay" style="display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.5); z-index: 999;" onclick="document.getElementById('Abstract_Nath_2023').style.display='none'; document.getElementById('OVERLAY_Abstract_Nath_2023').style.display='none'">
</div>
<div id="OVERLAY_Abstract_Nath_2022_Ad_KL" class="overlay" style="display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.5); z-index: 999;" 
     onclick="document.getElementById('Abstract_Nath_2022_Ad_KL').style.display='none'; document.getElementById('OVERLAY_Abstract_Nath_2022_Ad_KL').style.display='none'">
</div>
<div id="OVERLAY_Abstract_Nath_2021_IPDD" class="overlay" style="display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.5); z-index: 999;" 
     onclick="document.getElementById('Abstract_Nath_2021_IPDD').style.display='none'; document.getElementById('OVERLAY_Abstract_Nath_2021_IPDD').style.display='none'">
</div>
<div id="OVERLAY_Abstract_Nath_2020_TDgPC" class="overlay" style="display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.5); z-index: 999;" 
     onclick="document.getElementById('Abstract_Nath_2020_TDgPC').style.display='none'; document.getElementById('OVERLAY_Abstract_Nath_2020_TDgPC').style.display='none'">
</div>
<div id="OVERLAY_Abstract_Nath_2019_IPC_Non_Gauss" class="overlay" style="display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.5); z-index: 999;" 
     onclick="document.getElementById('Abstract_Nath_2019_IPC_Non_Gauss').style.display='none'; document.getElementById('OVERLAY_Abstract_Nath_2019_IPC_Non_Gauss').style.display='none'">
</div>
<div id="OVERLAY_Abstract_Nath_2019_IPC_Gauss" class="overlay" style="display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.5); z-index: 999;" 
     onclick="document.getElementById('Abstract_Nath_2019_IPC_Gauss').style.display='none'; document.getElementById('OVERLAY_Abstract_Nath_2019_IPC_Gauss').style.display='none'">
</div>


<!-- Overlay CITE -->
<div id="OVERLAY_CITE_Mariappan_2024_PINN" class="overlay" style="display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.5); z-index: 999;" 
     onclick="document.getElementById('CITE_Mariappan_2024_PINN').style.display='none'; document.getElementById('OVERLAY_CITE_Mariappan_2024_PINN').style.display='none'">
</div>
<div id="OVERLAY_CITE_Felipe_2024_PINN" class="overlay" style="display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.5); z-index: 999;" 
     onclick="document.getElementById('CITE_Felipe_2024_PINN').style.display='none'; document.getElementById('OVERLAY_CITE_Felipe_2024_PINN').style.display='none'">
</div>
<div id="OVERLAY_CITE_Liu_2022_Causality" class="overlay" style="display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.5); z-index: 999;" 
     onclick="document.getElementById('CITE_Liu_2022_Causality').style.display='none'; document.getElementById('OVERLAY_CITE_Liu_2022_Causality').style.display='none'">
</div>
<div id="OVERLAY_CITE_Nath_2023" class="overlay" style="display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.5); z-index: 999;" 
     onclick="document.getElementById('CITE_Nath_2023').style.display='none'; document.getElementById('OVERLAY_CITE_Nath_2023').style.display='none'">
</div>
<div id="OVERLAY_CITE_Nath_2022_Ad_KL" class="overlay" style="display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.5); z-index: 999;" 
     onclick="document.getElementById('CITE_Nath_2022_Ad_KL').style.display='none'; document.getElementById('OVERLAY_CITE_Nath_2022_Ad_KL').style.display='none'">
</div>
<div id="OVERLAY_CITE_Nath_2021_IPDD" class="overlay" style="display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.5); z-index: 999;" 
     onclick="document.getElementById('CITE_Nath_2021_IPDD').style.display='none'; document.getElementById('OVERLAY_CITE_Nath_2021_IPDD').style.display='none'">
</div>
<div id="OVERLAY_CITE_Nath_2020_TDgPC" class="overlay" style="display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.5); z-index: 999;" 
     onclick="document.getElementById('CITE_Nath_2020_TDgPC').style.display='none'; document.getElementById('OVERLAY_CITE_Nath_2020_TDgPC').style.display='none'">
</div>
<div id="OVERLAY_CITE_Nath_2019_IPC_Non_Gauss" class="overlay" style="display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.5); z-index: 999;" 
     onclick="document.getElementById('CITE_Nath_2019_IPC_Non_Gauss').style.display='none'; document.getElementById('OVERLAY_CITE_Nath_2019_IPC_Non_Gauss').style.display='none'">
</div>
<div id="OVERLAY_CITE_Nath_2019_IPC_Gauss" class="overlay" style="display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.5); z-index: 999;" 
     onclick="document.getElementById('CITE_Nath_2019_IPC_Gauss').style.display='none'; document.getElementById('OVERLAY_CITE_Nath_2019_IPC_Gauss').style.display='none'">
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
    // Show a specific pop-up
    function showPopup(popupId) {
      const popup = document.getElementById(popupId);
      const overlay = document.getElementById(`overlay${popupId.slice(-1)}`);
      popup.style.display = 'block';
      overlay.style.display = 'block';
    }
    // Close a specific pop-up
    function closePopup(popupId) {
      const popup = document.getElementById(popupId);
      const overlay = document.getElementById(`overlay${popupId.slice(-1)}`);
      popup.style.display = 'none';
      overlay.style.display = 'none';
    }
    // Close pop-ups when clicking outside
    document.addEventListener('click', (event) => {
      const popups = document.querySelectorAll('.popup');
      popups.forEach((popup) => {
        const overlayId = `overlay${popup.id.slice(-1)}`;
        const overlay = document.getElementById(overlayId);
        if (
          popup.style.display === 'block' &&
          !popup.contains(event.target) &&
          !event.target.matches('button')
        ) {
          closePopup(popup.id);
        }
      });
    });
  </script>

<script>
  function copyToClipboard(text) {
  navigator.clipboard.writeText(text)
    .then(() => {
      console.log(`Copied text to clipboard: ${text}`);
    })
    .catch((error) => {
      console.error(`Could not copy text: ${error}`);
      alert(`Failed to copy text: ${error}`);
    });
}
function copyCITE(abstractId) {
  const abstractElement = document.getElementById(abstractId);

  if (!abstractElement) {
    console.error('Cite not copied!');
    alert('Copy error, Select and copy manually!');
    return;
  }

  const abstractText = abstractElement.innerText || abstractElement.textContent;
  copyToClipboard(abstractText);
}
</script>

<script>
  function ESCclose(evt) {
  if (evt.keyCode == 27) {
    //window.close();
    console.log('close the window...')
  }
}
</script>


