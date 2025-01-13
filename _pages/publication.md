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

.button {
  background-color: #04AA6D; /* Green */
  border: none;
  color: black;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 10px 4px;
  cursor: pointer;
}

.class_1 {background-color: #94e5ff; border-radius: 8px; } /* Blue  #008CBA*/
.red {background-color: #f44336;} /* Red */ 
.gray {background-color: #e7e7e7; color: black;} /* Gray */ 
</style>

<button onclick="myFunction()">
<i class="fa fa-adjust"></i>
</button>
<script>
function myFunction() {
   var element = document.body;
   element.classList.toggle("dark-mode");
}  
</script>

<a id="top"></a>
<a target="_blank" rel="noopener noreferrer" href = "https://scholar.google.co.in/citations?user=U9Vf1IwAAAAJ&hl=en"> Google Scholar profile </a>

* *Contributed equally

<!-- PRIPRINTS -->
<a id="Preprints"></a>
### Preprints
<ol  reversed="reversed">
  <p style='text-align: justify;'>
    <li> 
      <p style='text-align: justify;'>  <b>  Kamaljyoti Nath</b>, Varun Kumar, Daniel J. Smith, George Em Karniadakis (2024) <a target="_blank" rel="noopener noreferrer" href = "https://arxiv.org/abs/2412.11967">  A Digital twin for Diesel Engines: Operator-infused PINNs with Transfer Learning for Engine Health Monitoring </a>
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
  <p style='text-align: justify;'>
    <b>  Kamaljyoti Nath</b>, Anjan Dutta, Budhaditya Hazra (2021). <a target="_blank" rel="noopener noreferrer" href="https://www.taylorfrancis.com/chapters/edit/10.1201/9781003194613-8/stochastic-finite-element-method-kamaljyoti-nath-anjan-dutta-budhaditya-hazra?context=ubx&refId=07d53908-1c18-4fad-9beb-be78b05e9096">  Stochastic Finite Element Method </a>. In: Farsangi, E.N., Noori, M., Gardoni, P., Takewaki, I., Varum, H., & Bogdanovic, A. (Eds.) <a href ="https://doi.org/10.1201/9781003194613">  <i> Reliability-Based Analysis and Design of Structures and Infrastructure (1st ed.) </i> </a> (pp. 101-116). CRC Press. 
<br>
<a target="_blank" rel="noopener noreferrer" href= "https://books.google.co.in/books?hl=en&lr=&id=WV9CEAAAQBAJ&oi=fnd&pg=PA101&ots=ZV74-odli1&sig=sVMdlkKYhhjAPrOLcX4J8R7U1VQ#v=onepage&q&f=false"> <button class="class_1"> Read on Google Book</button> </a> 
<!--
<button onclick="document.getElementById('CITE_Nath_2021_SFEM_Chapter').style.display='block'" class="class_1"> Cite </button>
<div id="CITE_Nath_2021_SFEM_Chapter" style="display: none; position: fixed; top: 20%; right: 2%; width: 40%; height: auto; background-color: rgba(0, 0, 0, 0.7);">
    <div style="position: absolute; background-color: white; margin: 10px; padding: 10px; width: 100%; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
      <span onclick="document.getElementById('CITE_Nath_2021_SFEM_Chapter').style.display='none'" style="color: #aaa; font-size: 28px; font-weight: bold; float: right;">&times;</span>
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
  
</p> </li>
</p>
</ol>

<!-- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- -->
<a id="Journal"></a>
### Journals
<ol reversed="reversed"> <p style='text-align: justify;'>
<!-- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- -->
<li>
<p style='text-align: justify;'>
  Sathesh Mariappan, <b>Kamaljyoti Nath</b>, George Em Karniadakis (2024), Learning thermoacoustic interactions in combustors using a physics-informed neural network. <i> Engineering Applications of Artificial Intelligence </i>, 138, 109388.
  <details>
  <summary>Abstract</summary>
Many gas turbine and rocket engines exhibit unwanted combustion instability at the experimental testing phase. Instability leads to large amplitude pressure oscillations and increased heat transfer damaging the engine. Data obtained during such tests can be used to prescribe appropriate engine modifications. In many tests, acoustic pressure is measured at few locations, and acoustic velocity is seldom measured. Physics-informed neural network (PINN) method is a potential remedy, by combining the experimental data and governing equations to reconstruct the acoustic field. We employ a PINN to investigate thermoacoustic interactions in a bluff body anchored flame combustor, representative of ramjet and gas turbine combustors. Acoustic pressure fluctuations at three locations and the total flame heat release rate serve as the measured data. The coupled parameterized model (governing equations) comprises the acoustic equations and the van der Pol oscillator for vortex shedding. We have the challenges of unknown initial/boundary conditions, absence of acoustic velocity measurements, and variation of the acoustic pressure amplitude in a long time scale due to the turbulent flame. Therefore, PINN requires novel enhancements to its training procedure. The enhancements (i) systematically adjusting the relative contribution of the various loss terms, (ii) inclusion of a loss term associated with acoustic velocity, and (iii) time series segmentation, are respectively implemented. PINN performs well in generating the acoustic field and estimating the model parameters. Therefore, this PINN method can serve as an effective tool to improve existing or design new thermoacoustically stable and structurally efficient combustors.
 </details>
  <br>
  <a target="_blank" rel="noopener noreferrer" href = "https://doi.org/10.1016/j.engappai.2024.109388"> <button class="class_1">Journal</button></a>
  <a target="_blank" rel="noopener noreferrer" href="https://doi.org/10.48550/arXiv.2401.00061" ><button class="class_1">arXiv</button></a>
  <button onclick="document.getElementById('CITE_Mariappan_2024_PINN').style.display='block'" class="class_1"> Cite </button>

  <div id="CITE_Mariappan_2024_PINN" style="display: none; position: fixed; top: 20%; right: 2%; width: 40%; height: auto; background-color: rgba(0, 0, 0, 0.7);">
    <div style="position: absolute; background-color: white; margin: 10px; padding: 10px; width: 100%; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
      <span onclick="document.getElementById('CITE_Mariappan_2024_PINN').style.display='none'" style="color: #aaa; font-size: 28px; font-weight: bold; float: right;">&times;</span>
      <h3 style="font-size: 18px;" style="color:blue;">Cite Article</h3>
      <pre style="font-size: 12px;" style="color:blue;">
@article{Mariappan_2024_PINN,
  author = {Sathesh Mariappan and Kamaljyoti Nath and George Em Karniadakis}
  title = {Learning thermoacoustic interactions in combustors using a physics-informed neural network},
  journal = {Engineering Applications of Artificial Intelligence},
  volume = {138},
  pages = {109388},
  year = {2024},
  issn = {0952-1976},
  doi = {https://doi.org/10.1016/j.engappai.2024.109388},
  url = {https://www.sciencedirect.com/science/article/pii/S095219762401546X}
}
      </pre>
    </div>
  </div>   
</p>
</li> 
  
<!-- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- -->  
<li>
<p style='text-align: justify;'>
  Felipe de Castro Teixeira Carvalho, <b>Kamaljyoti Nath</b>, Alberto Luiz Serpa, George Em Karniadakis (2024), Learning characteristic parameters and dynamics of centrifugal pumps under multiphase flow using physics-informed neural networks. <i> Engineering Applications of Artificial Intelligence </i>, 138, 109378. 
  <br>
  <a target="_blank" rel="noopener noreferrer" href = "https://doi.org/10.1016/j.engappai.2024.109378"> <button class="class_1">Journal</button></a>
  <a target="_blank" rel="noopener noreferrer" href="https://doi.org/10.48550/arXiv.2310.03001" ><button class="class_1">arXiv</button></a>
  <button onclick="document.getElementById('CITE_Felipe_2024_PINN').style.display='block'" class="class_1"> Cite </button>

  <div id="CITE_Felipe_2024_PINN" style="display: none; position: fixed; top: 20%; right: 2%; width: 40%; height: auto; background-color: rgba(0, 0, 0, 0.7);">
    <div style="position: absolute; background-color: white; margin: 10px; padding: 10px; width: 100%; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
      <span onclick="document.getElementById('CITE_Felipe_2024_PINN').style.display='none'" style="color: #aaa; font-size: 28px; font-weight: bold; float: right;">&times;</span>
      <h3 style="font-size: 18px;" style="color:blue;">Cite Article</h3>
      <pre style="font-size: 12px;" style="color:blue;">
@article{Felipe_2024_PINN,
  author = {Felipe de Castro Teixeira Carvalho and Kamaljyoti Nath and Alberto Luiz Serpa and George Em Karniadakis},
  title = {Learning characteristic parameters and dynamics of centrifugal pumps under multiphase flow using physics-informed neural networks},
  journal = {Engineering Applications of Artificial Intelligence},
  volume = {138},
  pages = {109378},
  year = {2024},
  issn = {0952-1976},
  doi = {https://doi.org/10.1016/j.engappai.2024.109378},
  url = {https://www.sciencedirect.com/science/article/pii/S0952197624015367},
  keywords = {Electrical submersible pump, Physics-informed neural networks, Parameters estimation, Identifiability analysis, Multiphase flow, Digital twin}
}   
      </pre>
    </div>
  </div> 
</p>
</li>
<!-- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- -->
<li>
<p style='text-align: justify;' > 
  Lizuo Liu, <b>Kamaljyoti Nath</b>, Wei Cai (2024), A Causality-DeepONet for Causal Responses of Linear Dynamical Systems. <i>Communications in Computational Physics</i>, 35 (5), 1194-1228.
  <br>
  <a target="_blank" rel="noopener noreferrer" href="https://doi.org/10.4208/cicp.OA-2023-0078"><button  class="class_1">Journal</button></a> 
  <a target="_blank" rel="noopener noreferrer" href="https://doi.org/10.48550/arXiv.2209.08397" > <button  class="class_1">arXiv</button> </a> 
  <a target="_blank" rel="noopener noreferrer" href="https://www.researchgate.net/publication/381733362_A_Causality-DeepONet_for_Causal_Responses_of_Linear_Dynamical_Systems" > <button class="class_1"> ResearchGate </button>  </a> 
  <button onclick="document.getElementById('CITE_Liu_2022_Causality').style.display='block'" class="class_1"> Cite </button>

<div id="CITE_Liu_2022_Causality" style="display: none; position: fixed; top: 20%; right: 2%; width: 40%; height: auto; background-color: rgba(0, 0, 0, 0.7);">
  <div style="position: absolute; background-color: white; margin: 10px; padding: 10px; width: 100%; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
    <span onclick="document.getElementById('CITE_Liu_2022_Causality').style.display='none'" style="color: #aaa; font-size: 28px; font-weight: bold; float: right;">&times;</span>
    <h3 style="font-size: 18px;" style="color:blue;">Cite Article</h3>
    <pre style="font-size: 12px;" style="color:blue;">
@article{Liu_2022_Causality,
  author = {Liu , Lizuo and Nath , Kamaljyoti and Cai , Wei},
  title = {A Causality-DeepONet for Causal Responses of Linear Dynamical Systems},
  journal = {Communications in Computational Physics},
  year = {2024},
  volume = {35},
  number = {5},
  pages = {1194--1228},
  issn = {1991-7120},
  doi = {https://doi.org/10.4208/cicp.OA-2023-0078},
  url = {http://global-sci.org/intro/article_detail/cicp/23189.html}
}  
    </pre>
  </div>
</div> 
 
</p>
</li> 
<!-- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- -->
  
<li>
<p style='text-align: justify;'>
    <b>Kamaljyoti Nath</b>*, Xuhui Meng*, Daniel J Smith, George Em Karniadakis (2023) Physics-informed neural networks for predicting gas flow dynamics and unknown parameters in diesel engines. <i>Scientific Reports</i>, 13, 13683.
   <br>
  <a target="_blank" rel="noopener noreferrer" href = "https://doi.org/10.1038/s41598-023-39989-4"> <button class="class_1">Journal-Open Access</button></a>
  <button onclick="document.getElementById('CITE_Nath_2023').style.display='block'" class="class_1"> Cite </button>

  <div id="CITE_Nath_2023" style="display: none; position: fixed; top: 20%; right: 2%; width: 40%; height: auto; background-color: rgba(0, 0, 0, 0.7);">
    <div style="position: absolute; background-color: white; margin: 10px; padding: 10px; width: 100%; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
      <span onclick="document.getElementById('CITE_Nath_2023').style.display='none'" style="color: #aaa; font-size: 28px; font-weight: bold; float: right;">&times;</span>
      <h3 style="font-size: 18px;" style="color:blue;">Cite Article</h3>
      <pre style="font-size: 12px;" style="color:blue;">
@article{Nath_2023,
  title   = {Physics-informed neural networks for predicting gas flow dynamics and unknown parameters in diesel engines},
  author  = {Nath, Kamaljyoti and Meng, Xuhui and Smith, Daniel J. and Karniadakis, George Em},
  journal = {Scientific Reports},
  year    = {2023},
  volume  = {13},
  pages   = {13683},
  doi     = {10.1038/s41598-023-39989-4}	
}
      </pre>
    </div>
  </div>
</p>
</li>
<!-- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- -->
<li>
<p style='text-align: justify;'>
    <b>Kamaljyoti Nath</b>, Anjan Dutta, Budhaditya Hazra (2021) Iterative Polynomial Dimensional Decomposition approach towards solution of structural mechanics problems with material randomness. <i>Probabilistic Engineering Mechanics</i>, 66, 103159.
  <br>
  <a target="_blank" rel="noopener noreferrer" href = "https://doi.org/10.1016/j.probengmech.2021.103159"> <button class="class_1">Journal</button></a>
  <button onclick="document.getElementById('CITE_Nath_2021_IPDD').style.display='block'" class="class_1"> Cite </button>

  <div id="CITE_Nath_2021_IPDD" style="display: none; position: fixed; top: 20%; right: 2%; width: 40%; height: auto; background-color: rgba(0, 0, 0, 0.7);">
    <div style="position: absolute; background-color: white; margin: 10px; padding: 10px; width: 100%; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
      <span onclick="document.getElementById('CITE_Nath_2021_IPDD').style.display='none'" style="color: #aaa; font-size: 28px; font-weight: bold; float: right;">&times;</span>
      <h3 style="font-size: 18px;" style="color:blue;">Cite Article</h3>
      <pre style="font-size: 12px;" style="color:blue;">
@article{Nath_2021_IPDD,
  author = {Kamaljyoti Nath and Anjan Dutta and Budhaditya Hazra},
  title = {Iterative Polynomial Dimensional Decomposition approach towards solution of structural mechanics problems with material randomness},
  journal = {Probabilistic Engineering Mechanics},
  volume = {66},
  pages = {103159},
  year = {2021},
  issn = {0266-8920},
  doi = {https://doi.org/10.1016/j.probengmech.2021.103159},
  url = {https://www.sciencedirect.com/science/article/pii/S0266892021000436},
  keywords = {Stochastic Finite Element Method, Karhunen–Loève expansion, Polynomial Chaos expansion, Polynomial Dimensional Decomposition, Iterative Polynomial Chaos}
}
      </pre>
    </div>
  </div>
</p>
</li>
<!-- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- -->
<li>
  <p style='text-align: justify;'>
    <b>Kamaljyoti Nath</b>, Anjan Dutta, Budhaditya Hazra (2021) An adaptive scheme for random field discretization using KL expansion. <i>Engineering with Computers</i>, 38, 2937–2954.
  <br>
  <a target="_blank" rel="noopener noreferrer" href = "https://doi.org/10.1007/s00366-021-01326-6"> <button class="class_1">Journal</button></a>
  <!-- <button onclick="document.getElementById('CITE_Nath_2021_IPDD').style.display='block'" class="class_1"> Cite </button>

  <div id="CITE_Nath_2021_IPDD" style="display: none; position: fixed; top: 20%; right: 2%; width: 40%; height: auto; background-color: rgba(0, 0, 0, 0.7);">
    <div style="position: absolute; background-color: white; margin: 10px; padding: 10px; width: 100%; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
      <span onclick="document.getElementById('CITE_Nath_2021_IPDD').style.display='none'" style="color: #aaa; font-size: 28px; font-weight: bold; float: right;">&times;</span>
      <h3 style="font-size: 18px;" style="color:blue;">Cite Article</h3>
      <pre style="font-size: 12px;" style="color:blue;">
@article{Nath_2021_IPDD,
  author = {Kamaljyoti Nath and Anjan Dutta and Budhaditya Hazra},
  title = {Iterative Polynomial Dimensional Decomposition approach towards solution of structural mechanics problems with material randomness},
  journal = {Probabilistic Engineering Mechanics},
  volume = {66},
  pages = {103159},
  year = {2021},
  issn = {0266-8920},
  doi = {https://doi.org/10.1016/j.probengmech.2021.103159},
  url = {https://www.sciencedirect.com/science/article/pii/S0266892021000436},
  keywords = {Stochastic Finite Element Method, Karhunen–Loève expansion, Polynomial Chaos expansion, Polynomial Dimensional Decomposition, Iterative Polynomial Chaos}
}
      </pre>
    </div>
  </div> --> 	
  </p>
</li>
<!-- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- -->
<li>
  <p style='text-align: justify;'>
    <b>Kamaljyoti Nath</b>, Anjan Dutta, Budhaditya Hazra (2020) Long duration response evaluation of linear structural system with random system properties using time dependent polynomial chaos. <i>Journal of Computational Physics</i>, 418, 109596.
<br>
  <a target="_blank" rel="noopener noreferrer" href = "https://doi.org/10.1016/j.jcp.2020.109596"> <button class="class_1">Journal</button></a>
  <button onclick="document.getElementById('CITE_Nath_2021_IPDD').style.display='block'" class="class_1"> Cite </button>

  <div id="CITE_Nath_2020_Long" style="display: none; position: fixed; top: 20%; right: 2%; width: 40%; height: auto; background-color: rgba(0, 0, 0, 0.7);">
    <div style="position: absolute; background-color: white; margin: 10px; padding: 10px; width: 100%; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
      <span onclick="document.getElementById('CITE_Nath_2020_Long').style.display='none'" style="color: #aaa; font-size: 28px; font-weight: bold; float: right;">&times;</span>
      <h3 style="font-size: 18px;" style="color:blue;">Cite Article</h3>
      <pre style="font-size: 12px;" style="color:blue;">
@article{Nath_2020_Long,
  author = {Kamaljyoti Nath and Anjan Dutta and Budhaditya Hazra},
  title = {Long duration response evaluation of linear structural system with random system properties using time dependent polynomial chaos},
  journal = {Journal of Computational Physics},
  volume = {418},
  pages = {109596},
  year = {2020},
  issn = {0021-9991},
  doi = {https://doi.org/10.1016/j.jcp.2020.109596},
  url = {https://www.sciencedirect.com/science/article/pii/S0021999120303703},
  keywords = {Stochastic finite element method, Karhunen-Loève expansion, Polynomial chaos expansion, Stochastic dynamics, Time dependent generalized polynomial chaos}
 }
      </pre>
    </div>
  </div>
  </p>
</li>
<!-- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- -->
<li>
  <p style='text-align: justify;'>
    <b>Kamaljyoti Nath</b>, Anjan Dutta, Budhaditya Hazra (2019) An iterative polynomial chaos approach toward stochastic elastostatic structural analysis with non‐Gaussian randomness.  <i>International Journal for Numerical Methods in Engineering</i>, 119(11), 1126-1160. 
<br>
  <a target="_blank" rel="noopener noreferrer" href = "https://doi.org/10.1002/nme.6086"> <button class="class_1">Journal</button></a>
  <button onclick="document.getElementById('CITE_Nath_2019_IPC_Non_Gauss').style.display='block'" class="class_1"> Cite </button>

  <div id="CITE_Nath_2019_IPC_Non_Gauss" style="display: none; position: fixed; top: 20%; right: 2%; width: 40%; height: auto; background-color: rgba(0, 0, 0, 0.7);">
    <div style="position: absolute; background-color: white; margin: 10px; padding: 10px; width: 100%; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
      <span onclick="document.getElementById('CITE_Nath_2019_IPC_Non_Gauss').style.display='none'" style="color: #aaa; font-size: 28px; font-weight: bold; float: right;">&times;</span>
      <h3 style="font-size: 18px;" style="color:blue;">Cite Article</h3>
      <pre style="font-size: 12px;" style="color:blue;">
@article{Nath_2019_IPC_Non_Gauss,
  author = {Nath, Kamaljyoti and Dutta, Anjan and Hazra, Budhaditya},
  title = {An iterative polynomial chaos approach toward stochastic elastostatic structural analysis with non-Gaussian randomness},
  journal = {International Journal for Numerical Methods in Engineering},
  year = {2019},
  volume = {119},
  number = {11},
  pages = {1126-1160},
  keywords = {independent component analysis, Karhunen-Loève expansion, non-Gaussian material property, orthogonal expansion, polynomial chaos expansion},
  doi = {https://doi.org/10.1002/nme.6086},
  url = {https://onlinelibrary.wiley.com/doi/abs/10.1002/nme.6086},
  eprint = {https://onlinelibrary.wiley.com/doi/pdf/10.1002/nme.6086}
}
      </pre>
    </div>
  </div>
  </p>
</li>
<!-- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- -->
<li> 
  <p style='text-align: justify;'>
    <b>Kamaljyoti Nath</b>, Anjan Dutta, Budhaditya Hazra (2019) An iterative polynomial chaos approach for solution of structural mechanics problem with Gaussian material property. <i> Journal of Computational Physics </i>, 390, 425-451. 

<br>
  <a target="_blank" rel="noopener noreferrer" href = "https://doi.org/10.1016/j.jcp.2019.04.014"> <button class="class_1">Journal</button></a>
  <button onclick="document.getElementById('CITE_Nath_2019_IPC_Non_Gauss').style.display='block'" class="class_1"> Cite </button>

  <div id="CITE_Nath_Nath_2019_IPC_Gauss" style="display: none; position: fixed; top: 20%; right: 2%; width: 40%; height: auto; background-color: rgba(0, 0, 0, 0.7);">
    <div style="position: absolute; background-color: white; margin: 10px; padding: 10px; width: 100%; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
      <span onclick="document.getElementById('CITE_Nath_2019_IPC_Gauss').style.display='none'" style="color: #aaa; font-size: 28px; font-weight: bold; float: right;">&times;</span>
      <h3 style="font-size: 18px;" style="color:blue;">Cite Article</h3>
      <pre style="font-size: 12px;" style="color:blue;">
@article{Nath_2019_IPC_Gauss,
  title = {An iterative polynomial chaos approach for solution of structural mechanics problem with Gaussian material property},
  journal = {Journal of Computational Physics},
  volume = {390},
  pages = {425-451},
  year = {2019},
  issn = {0021-9991},
  doi = {https://doi.org/10.1016/j.jcp.2019.04.014},
  url = {https://www.sciencedirect.com/science/article/pii/S0021999119302475},
  author = {Kamaljyoti Nath and Anjan Dutta and Budhaditya Hazra},
  keywords = {Stochastic Finite Element Method, Karhunen-Loève expansion, Polynomial Chaos expansion}
}
      </pre>
    </div>
  </div>
  </p>
</li>
<!-- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- -->
</p></ol>

<!-- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- ---- -->
### Conference
<ol reversed="reversed"> <p style='text-align: justify;'>
<li> <p style='text-align: justify;'>  Amartya Dutta, <b> Kamaljyoti Nath</b> (2020). <a target="_blank" rel="noopener noreferrer" href ="https://doi.org/10.1007/978-981-16-3690-5_31"> Learning via Long Short-Term Memory (LSTM) Network for Predicting Strains in Railway Bridge Members Under Train Induced Vibration.</a> 2nd International Conference on Data Science, Machine Learning and Applications (ICDSMLA) 2020 (held virtually), Pune, India. In: Kumar A., Senatore S., Gunjan V.K. (eds) Lecture Notes in Electrical Engineering, vol 783 (pp. 351-361). Springer, Singapore. https://doi.org/10.1007/978-981-16-3690-5_31  </p> </li>
</p>
</ol> 

<a href="#top"> <button class="class_1"> Back to top </button> </a> 
<a href="#Book chapter"> <button class="class_1"> Back to Book chapter </button> </a> 
<a href="#Journal"> <button class="class_1"> Back to Journals </button>  </a>


