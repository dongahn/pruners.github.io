+++
date = "2017-01-27T22:16:29-07:00"
title = "Ninja"
parent = "toolset"
+++

<h1><span style="font-variant: small-caps;">Ninja</span></h1>


---
## Description
<img src="../img/NINJA_logo.png" width="40%" alt="NINJA Logo" title="ReMPI" align="right" style="margin-left: 20px; margin-right: 20px;"/>
<span style="font-variant: small-caps;"><b>Ninja</b></span> (Noise INJection Agent) is a smart network noise injector
for quickly exposing unintended MPI message races.
<span style="font-variant: small-caps;">Ninja</span> uses innovative network noise injection
techniques to increase the chances of racy, incorrect MPI message matching within the target
MPI application. <span style="font-variant: small-caps;"><b>Ninja</b></span> has been shown to reproduce unsafe message races consistently within
large production applications and can do this up to two orders of magnitude faster than the
traditional testing approach (i.e., random noise injection).

---
## Software

<span style="font-variant: small-caps;">Ninja</span> is open-source software and can be obtained on <a class="smooth-link" title="GitHub" href="https://github.com/PRUNERS/NINJA" target="_blank"><u>GitHub</u></a> <i class="fa fa-github"></i>.

---
## Quick Start

### Installation

1. **Spack: Recommended for curious users**

	<b><span style="font-variant: small-caps;">Ninja</span></b> maintains an up-to-date package in the Spack develop branch, which builds all dependencies and <b><span style="font-variant: small-caps;">Ninja</span></b> itself. To install via Spack run:

	```console
	$ git clone https://github.com/LLNL/spack
	$ spack/bin/spack install pruners-ninja
	```

	If you already have Spack, you can omit the first line.


2. **Manual: Recommended for developers and contributors**

	Please refer to the installation instructions in <a class="smooth-link" title="README" href="https://github.com/PRUNERS/NINJA/blob/master/README.md" target="_blank">README.md</a>.

---
## Reference
- Kento Sato, Dong H. Ahn, Ignacio Laguna, Gregory L. Lee, Martin Schulz and Christopher M. Chambreau, "Noise Injection Techniques for Reproducing Subtle and Unintended Message Races", Proceedings of the 20th ACM SIGPLAN Symposium on Principles and Practice of Parallel Programming (PPoPP17), Austin, USA, Feb, 2017.
