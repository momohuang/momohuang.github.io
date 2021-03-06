---
layout: post
title:  "Biomedical SpaCy: BioBio"
date:   2018-09-01
excerpt: "An easy-to-use natural language processing tool for biomedical texts (based on SpaCy)."
project: true
is_featured: true
feature_fig:
is_redirected: true
redirection_url: https://sites.google.com/view/biomedical-spacy/home
tag:
- Side Project
- Bioinformatics
- Natural language processing
- Machine learning
comments: true
---

<figure>
	<img src="{{site.url}}/assets/img/CompQM/FGH.jpg">
</figure>

<center>
	<a href="https://github.com/momohuang/computational-quantum-mechanics" target="_blank" class="btn">
		<span style="font-size: 120%;">
		GitHub
		</span>
	</a>
	&nbsp;
	<a href="https://youtu.be/tgJXdQFXmN0" target="_blank" class="btn">
		<span style="font-size: 120%;">
		YouTube
		</span>
	</a>
	&nbsp;
	<a href="https://goo.gl/PP5vNZ" target="_blank" class="btn">
		<span style="font-size: 120%;">
		Collection 1
		</span>
	</a>
	&nbsp;
	<a href="https://goo.gl/lnhQGO" target="_blank" class="btn">
		<span style="font-size: 120%;">
		Collection 2
		</span>
	</a>
	&nbsp;
	<a href="{{ site.baseurl }}/assets/img/FGH_and_QMC.pdf" target="_blank" class="btn">
		<span style="font-size: 120%;">
		Tech. Report
		</span>
	</a>
</center>

<p>While quantum mechanics can accurately describe our universe, the equation governing the quantum system is too complicated to be soluble through human analysis. To apply this great theory to real world scenarios, such as in the investigation of electronic structure or in the prediction of complex system in atomic scale, we have to resort to computational approach. In this project, I studied and implemented two well-known approach for solving the properties of quantum systems: <strong>the Fourier grid Hamiltonian method</strong> and <strong>Quantum Monte Carlo method</strong>.
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Fourier grid Hamiltonian (FGH) method elegantly discretized the problem through momentum space representation into an finite Eigenvalue problem. The eigenvalue decomposition is solved using <a href="http://eigen.tuxfamily.org/index.php?title=Main_Page" target="_blank">Eigen Library</a> in my implementation. The above artistic figures are electron excited states computed using this method. The lowest 150 excited states for 2D simple harmonic oscillator and for a special potential can be found <a href="https://goo.gl/PP5vNZ" target="_blank">here</a> and <a href="https://goo.gl/lnhQGO" target="_blank">here</a> on DropBox.
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Quantum Monte Carlo (QMC) method is an interesting algorithm that can efficiently solve for the ground state property of any multiple-Boson system. The idea is to propagate in the imaginary time through <a href="https://en.wikipedia.org/wiki/Path_integral_formulation">Feynman's Path Integral Formulation</a>. And by viewing the imaginary time propagation as a birth-death process with random walking replicas. A visualization of this method is available on <a href="https://youtu.be/tgJXdQFXmN0" target="_blank">YouTube</a>. I have also implemented some real-world situations to demonstrate the effectiveness of this method.</p>
