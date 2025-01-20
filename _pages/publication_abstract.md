
  

<!-- -------- -------- -------- -------- -------- ---- -------- -------- -------- -------- -------- -------- -------- -------- -------- -------- -------- -------- -------- -------- -->
<!-- ----------------Abstract------------------ -->
<div id="Abstract_Mariappan_2024_PINN" class="popup" style="display: none; position: fixed; top: 20%; left: 50%; transform: translate(-50%, -20%); width: 50%; background-color: white; z-index: 1000; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
<div style="position: relative; margin: 10px; padding: 10px;">
<span onclick="document.getElementById('Abstract_Mariappan_2024_PINN').style.display='none; document.getElementById('OVERLAY_Abstract_Mariappan_2024_PINN').style.display='none'" 
          style="color: #aaa; font-size: 28px; font-weight: bold; float: right; cursor: pointer;"> </span>
<h2 style="font-size: 18px; color:blue;">Learning thermoacoustic interactions in combustors using a physics-informed neural network</h2>
<h3 style="font-size: 18px; color:blue;">Abstract</h3>
<p class="p_class_1">
Many gas turbine and rocket engines exhibit unwanted combustion instability at the experimental testing phase. Instability leads to large amplitude pressure oscillations and increased heat transfer damaging the engine. Data obtained during such tests can be used to prescribe appropriate engine modifications. In many tests, acoustic pressure is measured at few locations, and acoustic velocity is seldom measured. Physics-informed neural network (PINN) method is a potential remedy, by combining the experimental data and governing equations to reconstruct the acoustic field. We employ a PINN to investigate thermoacoustic interactions in a bluff body anchored flame combustor, representative of ramjet and gas turbine combustors. Acoustic pressure fluctuations at three locations and the total flame heat release rate serve as the measured data. The coupled parameterized model (governing equations) comprises the acoustic equations and the van der Pol oscillator for vortex shedding. We have the challenges of unknown initial/boundary conditions, absence of acoustic velocity measurements, and variation of the acoustic pressure amplitude in a long time scale due to the turbulent flame. Therefore, PINN requires novel enhancements to its training procedure. The enhancements (i) systematically adjusting the relative contribution of the various loss terms, (ii) inclusion of a loss term associated with acoustic velocity, and (iii) time series segmentation, are respectively implemented. PINN performs well in generating the acoustic field and estimating the model parameters. Therefore, this PINN method can serve as an effective tool to improve existing or design new thermoacoustically stable and structurally efficient combustors.
</p>
<button onclick="document.getElementById('Abstract_Mariappan_2024_PINN').style.display='none'; document.getElementById('OVERLAY_Abstract_Mariappan_2024_PINN').style.display='none'" style="margin-top: 
 10px;">Close</button>  
</div>
</div>
<!-- --------------------------------------------- -->
<div id="Abstract_Felipe_2024_PINN" class="popup" style="display: none; position: fixed; top: 20%; left: 50%; transform: translate(-50%, -20%); width: 50%; background-color: white; z-index: 1000; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
  <div style="position: relative; margin: 10px; padding: 10px;">
    <span onclick="document.getElementById('Abstract_Felipe_2024_PINN').style.display='none'; document.getElementById('OVERLAY_Abstract_Felipe_2024_PINN').style.display='none'" 
          style="color: #aaa; font-size: 28px; font-weight: bold; float: right; cursor: pointer;"> </span>
    <h2 style="font-size: 18px; color: blue;">Learning characteristic parameters and dynamics of centrifugal pumps under multiphase flow using physics-informed neural networks</h2>
    <h3 style="font-size: 18px; color: blue;">Abstract</h3>
    <p class="p_class_1">
      Electrical submersible pumps (ESPs) are prevalently utilized as artificial lift systems in the oil and gas industry. These pumps frequently encounter multiphase flows comprising a complex mixture of hydrocarbons, water, and sediments. Such mixtures lead to the formation of emulsions, characterized by an effective viscosity distinct from that of the individual phases. Traditional multiphase flow meters, employed to assess these conditions, are burdened by high operational costs and susceptibility to degradation. To this end, this study introduces a physics-informed neural network (PINN) model designed to indirectly estimate the fluid properties, dynamic states, and crucial parameters of an ESP system. A comprehensive structural and practical identifiability analysis was performed to delineate the subset of parameters that can be reliably estimated through the use of intake and discharge pressure measurements from the pump. The efficacy of the PINN model was validated by estimating the unknown states and parameters using these pressure measurements as input data. Furthermore, the performance of the PINN model was benchmarked against the particle filter method utilizing both simulated and experimental data across varying water content scenarios. The comparative analysis suggests that the PINN model holds significant potential as a viable alternative to conventional multiphase flow meters, offering a promising avenue for enhancing operational efficiency and reducing costs in ESP applications.
    </p>
    <button onclick="document.getElementById('Abstract_Felipe_2024_PINN').style.display='none'; document.getElementById('OVERLAY_Abstract_Felipe_2024_PINN').style.display='none'" style="margin-top: 
 10px;">Close</button>
  </div>
</div>
<!-- --------------------------------------------- -->

<div id="Abstract_Liu_2022_Causality" class="popup" style="display: none; position: fixed; top: 20%; left: 50%; transform: translate(-50%, -20%); width: 50%; background-color: white; z-index: 1000; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
  <div style="position: relative; margin: 10px; padding: 10px;">
    <span onclick="document.getElementById('Abstract_Liu_2022_Causality').style.display='none'; document.getElementById('OVERLAY_Abstract_Liu_2022_Causality').style.display='none'" 
          style="color: #aaa; font-size: 28px; font-weight: bold; float: right; cursor: pointer;"> </span>
    <h2 style="font-size: 18px; color: blue;"> A Causality-DeepONet for Causal Responses of Linear Dynamical Systems</h2>
    <h3 style="font-size: 18px; color: blue;">Abstract</h3>
    <p class="p_class_1">
      In this paper, we propose a DeepONet structure with causality to represent causal linear operators between Banach spaces of time-dependent signals. The theorem of universal approximations to nonlinear operators proposed in [5] is extended to operators with causalities, and the proposed Causality-DeepONet implements the physical causality in its framework. The proposed Causality-DeepONet considers causality (the state of the system at the current time is not affected by that of the future, but only by its current state and past history) and uses a convolution-type weight in its design. To demonstrate its effectiveness in handling the causal response of a physical system, the Causality-DeepONet is applied to learn the operator representing the response of a building due to earthquake ground accelerations. Extensive numerical tests and comparisons with some existing variants of DeepONet are carried out, and the Causality-DeepONet clearly shows its unique capability to learn the retarded dynamic responses of the seismic response operator with good accuracy.
    </p>
    <button onclick="document.getElementById('Abstract_Liu_2022_Causality').style.display='none'; document.getElementById('OVERLAY_Abstract_Liu_2022_Causality').style.display='none'" style="margin-top: 
 10px;">Close</button>
  </div>
</div>
<!-- --------------------------------------------- -->
<div id="Abstract_Nath_2023" class="popup" style="display: none; position: fixed; top: 20%; left: 50%; transform: translate(-50%, -20%); width: 50%; background-color: white; z-index: 1000; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
  <div style="position: relative; margin: 10px; padding: 10px;">
    <span onclick="document.getElementById('Abstract_Nath_2023').style.display='none'; document.getElementById('OVERLAY_Abstract_Nath_2023').style.display='none'" 
          style="color: #aaa; font-size: 28px; font-weight: bold; float: right; cursor: pointer;"> </span>
    <h2 style="font-size: 18px; color: blue;"> Physics-informed neural networks for predicting gas flow dynamics and unknown parameters in diesel engines</h2>
    <h3 style="font-size: 18px; color: blue;">Abstract</h3>
    <p class="p_class_1">
      This paper presents a physics-informed neural network (PINN) approach for monitoring the health of diesel engines. The aim is to evaluate the engine dynamics, identify unknown parameters in a “mean value” model, and anticipate maintenance requirements. The PINN model is applied to diesel engines with a variable-geometry turbocharger and exhaust gas recirculation, using measurement data of selected state variables. The results demonstrate the ability of the PINN model to predict simultaneously both unknown parameters and dynamics accurately with both clean and noisy data, and the importance of the self-adaptive weight in the loss function for faster convergence. The input data for these simulations are derived from actual engine running conditions, while the outputs are simulated data, making this a practical case study of PINN’s ability to predict real-world dynamical systems. The mean value model of the diesel engine incorporates empirical formulae to represent certain states, but these formulae may not be generalizable to other engines. To address this, the study considers the use of deep neural networks (DNNs) in addition to the PINN model. The DNNs are trained using laboratory test data and are used to model the engine-specific empirical formulae in the mean value model, allowing for a more flexible and adaptive representation of the engine’s states. In other words, the mean value model uses both the PINN model and the DNNs to represent the engine’s states, with the PINN providing a physics-based understanding of the engine’s overall dynamics and the DNNs offering a more engine-specific and adaptive representation of the empirical formulae. By combining these two approaches, the study aims to offer a comprehensive and versatile approach to monitoring the health and performance of diesel engines.
    </p>
    <button onclick="document.getElementById('Abstract_Nath_2023').style.display='none'; document.getElementById('OVERLAY_Abstract_Nath_2023').style.display='none'" style="margin-top: 
 10px;">Close</button>
  </div>
</div>

<!-- --------------------------------------------- -->
<div id="Abstract_Nath_2022_Ad_KL" class="popup" style="display: none; position: fixed; top: 20%; left: 50%; transform: translate(-50%, -20%); width: 50%; background-color: white; z-index: 1000; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
  <div style="position: relative; margin: 10px; padding: 10px;">
    <span onclick="document.getElementById('Abstract_Nath_2022_Ad_KL').style.display='none'; document.getElementById('OVERLAY_Abstract_Nath_2022_Ad_KL').style.display='none'" 
          style="color: #aaa; font-size: 28px; font-weight: bold; float: right; cursor: pointer;"> </span>
    <h2 style="font-size: 18px; color: blue;"> An adaptive scheme for random field discretization using KL expansion </h2>
    <h3 style="font-size: 18px; color: blue;">Abstract</h3>
    <p class="p_class_1">
With the increase in computational facilities, interest in probabilistic analysis of engineering structures are observed to grow for a realistic assessment of physical systems. While the probabilistic analyses are generally carried out considering random variable models of physical parameters, a spatially varying random field model is more realistic. A discretization method converts the continuous parameter random field to a set of random variables. Truncated Karhunen–Loève (KL) expansion is one of the popular methods for the discretization of a random field. An accurate discretization can be achieved by considering a fine mesh along with a large number of terms. However, an increase in the number of elements and/or inclusion of more terms leads to an increase in computational cost. It is also found that only an increase in the number of terms in the expansion or number of elements alone does not provide an accurate representation of the random field. An adaptive discretization strategy is presented, which will suitably discretize the concerned domain while ensuring that both global and local level errors are kept within the prescribed limit.
    </p>
    <button onclick="document.getElementById('Abstract_Nath_2022_Ad_KL').style.display='none'; document.getElementById('OVERLAY_Abstract_Nath_2022_Ad_KL').style.display='none'" style="margin-top: 
 10px;">Close</button>
  </div>
</div>
<!-- --------------------------------------------- -->
<div id="Abstract_Nath_2021_IPDD" class="popup" style="display: none; position: fixed; top: 20%; left: 50%; transform: translate(-50%, -20%); width: 50%; background-color: white; z-index: 1000; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
  <div style="position: relative; margin: 10px; padding: 10px;">
    <span onclick="document.getElementById('Abstract_Nath_2021_IPDD').style.display='none'; document.getElementById('OVERLAY_Abstract_Nath_2021_IPDD').style.display='none'" 
          style="color: #aaa; font-size: 28px; font-weight: bold; float: right; cursor: pointer;"> </span>
    <h2 style="font-size: 18px; color: blue;"> Iterative Polynomial Dimensional Decomposition approach towards solution of structural mechanics problems with material randomness </h2>
    <h3 style="font-size: 18px; color: blue;">Abstract</h3>
    <p class="p_class_1">
   One of the major difficulties in solving stochastic mechanics problems is the curse of dimensionality, where an exponential increase in the dimension of the problem is encountered with the increase in the number of random variables and/or order of expansion considered in any approximation. A prominent method in addressing the curse of dimensionality is ANOVA dimension Decomposition (ADD), which represents a mathematical function with multiple lower variate functions. These lower variate functions are represented using orthogonal polynomials, which yields Polynomial Dimensional Decomposition (PDD). In recent articles, the authors proposed an Iterative Polynomial Chaos (ImPC) based method for the solution of structural mechanics problems, where computational efficacy of ImPC was demonstrated against Polynomial Chaos (PC). In ImPC, the problems are solved iteratively using smaller sizes of PC expansions. Thus, it reduces the curse of dimensionality of PC expansion. The PDD reduces the size of the system matrix by considering a fewer number of random variables at a time, while ImPC can be considered to solve each components of PDD iteratively so that a converged solution can be achieved without increasing the order of expansion, which is termed as iterative PDD in the present study. Thus, the overall convergence can be achieved with a lesser size of the system matrix, which enables to perform analyses with a lesser computational facility. Further, the stiffness matrix size can be reduced by considering the random field at Gauss points instead of the mid point. Numerical studies with both Gaussian and non-Gaussian random field of Young’s modulus are conducted, and computational efficiency of the iterative PDD is compared with that of PDD, ImPC, and first order perturbation method. The iterative PDD is observed to be computationally less demanding and exhibits reduced dimensional curse.
    </p>
    <button onclick="document.getElementById('Abstract_Nath_2021_IPDD').style.display='none'; document.getElementById('OVERLAY_Abstract_Nath_2021_IPDD').style.display='none'" style="margin-top: 
 10px;">Close</button>
  </div>
</div>




<!-- --------------------------------------------- -->
<div id="Abstract_Nath_2020_TDgPC" class="popup" style="display: none; position: fixed; top: 20%; left: 50%; transform: translate(-50%, -20%); width: 50%; background-color: white; z-index: 1000; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
  <div style="position: relative; margin: 10px; padding: 10px;">
    <span onclick="document.getElementById('Abstract_Nath_2020_TDgPC').style.display='none'; document.getElementById('OVERLAY_Abstract_Nath_2020_TDgPC').style.display='none'" 
          style="color: #aaa; font-size: 28px; font-weight: bold; float: right; cursor: pointer;"> </span>
    <h2 style="font-size: 18px; color: blue;"> Long duration response evaluation of linear structural system with random system properties using time dependent polynomial chaos </h2>
    <h3 style="font-size: 18px; color: blue;">Abstract</h3>
    <p class="p_class_1">
Polynomial Chaos (PC) is one of the popular methods for approximate evaluation of responses of stochastic structural mechanics problems. In the case of a structural system under dynamic loading, the PC method is combined with a time integration scheme. The PC method with Galerkin projection converts the stochastic PDE to a set of simultaneous deterministic PDE, which can be solved using any standard time integration scheme. However, the convergence of responses is known to fail for long duration time integration problem due to the development of unacceptable error in calculated response. The probability density functions of the responses are not of constant type as the time progresses. However, in the case of generalized PC (gPC), these are approximated using initially considered gPC, thus loses its efficiency. Time-dependent general polynomial chaos (TDgPC) can be considered to overcome these difficulties, where polynomials are generated on the fly to match with the pdf of the responses. The present study considered an investigation of structural mechanics responses with both Gaussian and non-Gaussian random system properties under dynamic loading using TDgPC. An adaptive updation scheme based on the RMS value of the coefficients of PC expansion is investigated for a proper updation of PC expansion. The curse of dimensionality of PC expansion is addressed by considering only the dominant components of the responses evaluated using KL expansion. Further, starting with lower-order PC, the order of PC expansion is increased only after the first updation, thus reducing computational complexities.
    </p>
    <button onclick="document.getElementById('Abstract_Nath_2020_TDgPC').style.display='none'; document.getElementById('OVERLAY_Abstract_Nath_2020_TDgPC').style.display='none'" style="margin-top: 
 10px;">Close</button>
  </div>
</div>
<!-- --------------------------------------------- -->
<div id="Abstract_Nath_2019_IPC_Non_Gauss" class="popup" style="display: none; position: fixed; top: 20%; left: 50%; transform: translate(-50%, -20%); width: 50%; background-color: white; z-index: 1000; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
  <div style="position: relative; margin: 10px; padding: 10px;">
    <span onclick="document.getElementById('Abstract_Nath_2019_IPC_Non_Gauss').style.display='none'; document.getElementById('OVERLAY_Abstract_Nath_2019_IPC_Non_Gauss').style.display='none'" 
          style="color: #aaa; font-size: 28px; font-weight: bold; float: right; cursor: pointer;"> </span>
    <h2 style="font-size: 18px; color: blue;"> An iterative polynomial chaos approach toward stochastic elastostatic structural analysis with non‐Gaussian randomness </h2>
    <h3 style="font-size: 18px; color: blue;">Abstract</h3>
    <p class="p_class_1">
Stochastic analysis of structure with non-Gaussian material property and loading in the framework of polynomial chaos (PC) is considered. A new approach for the solution of stochastic mechanics problem with random coefficient is presented. The major focus of the method is to consider reduced size of expansion in an iterative manner to overcome the problem of large system matrix in conventional PC expansion. The iterative method is based on orthogonal expansion of stochastic responses and generation of an iterative PC based on the responses of the previous iteration. The polynomials are evaluated using Gram-Schmidt orthogonalization process. The numbers of random variables in PC expansion are reduced by considering only the dominant components of the response characteristics, which is evaluated using Karhunen-Loève (KL) expansion. In case of random material field problem, the KL expansion is used to discretize and simulate the non-Gaussian random field. Independent component analysis (ICA) is carried out on the non-Gaussian KL random variables to minimize statistical dependence. The usefulness of the proposed method in terms of accuracy and computational efficiency is examined. From the numerical analysis of three different types of structural mechanics problems, the proposed iterative method is observed to be computationally more efficient and accurate than conventional PC method for solution of linear elastostatic structural mechanics problems.
    </p>
    <button onclick="document.getElementById('Abstract_Nath_2019_IPC_Non_Gauss').style.display='none'; document.getElementById('OVERLAY_Abstract_Nath_2019_IPC_Non_Gauss').style.display='none'" style="margin-top: 
 10px;">Close</button>
  </div>
</div>

<!-- --------------------------------------------- -->
<div id="Abstract_Nath_2019_IPC_Gauss" class="popup" style="display: none; position: fixed; top: 20%; left: 50%; transform: translate(-50%, -20%); width: 50%; background-color: white; z-index: 1000; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
  <div style="position: relative; margin: 10px; padding: 10px;">
    <span onclick="document.getElementById('Abstract_Nath_2019_IPC_Gauss').style.display='none'; document.getElementById('OVERLAY_Abstract_Nath_2019_IPC_Gauss').style.display='none'" 
          style="color: #aaa; font-size: 28px; font-weight: bold; float: right; cursor: pointer;"> </span>
    <h2 style="font-size: 18px; color: blue;"> An iterative polynomial chaos approach for solution of structural mechanics problem with Gaussian material property </h2>
    <h3 style="font-size: 18px; color: blue;">Abstract</h3>
    <p class="p_class_1">
A new approach for solution of Stochastic structural Mechanics problem with random coefficient in the framework of Polynomial Chaos (PC) expansion is proposed. The basic strategy of the proposed method is to iteratively construct a PC expansion with reduced numbers of unknown coefficients. The method is based on orthogonal expansion of stochastic responses and generation of an iterative PC based on the responses of the previous iteration. The polynomials are evaluated using Gram-Schmidt orthogonalization process. The number of random variables in PC expansion is reduced by considering only the dominant components of the response characteristics, which is evaluated using Karhunen-Loève (KL) expansion. In case of random material field problem, KL expansion is used to discretize the random field. The usefulness of the proposed method in terms of accuracy and computational efficiency is examined. The results of linear static structural mechanics problems are compared with MCS and PC method. The proposed method is observed to be computationally more efficient and accurate than PC method.
    </p>
    <button onclick="document.getElementById('Abstract_Nath_2019_IPC_Gauss').style.display='none'; document.getElementById('OVERLAY_Abstract_Nath_2019_IPC_Gauss').style.display='none'" style="margin-top: 
 10px;">Close</button>
  </div>
</div>
