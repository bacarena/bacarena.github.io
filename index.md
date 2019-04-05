---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#layout: home
layout: default
---
<link href="//maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">


<center><i class="fa fa-bullhorn fa-5x" aria-hidden="true"></i></center>
<center><h1>Welcome to BacArena!</h1></center>
<p>&nbsp;</p>

BacArena is an open source software for simulating cellular communities. 
It combines agent-based modeling, flux balance analysis, and statistical analysis.
BacArena is implemented in R and available on [CRAN](https://cran.r-project.org/package=BacArena).

<p>&nbsp;</p>
**Get the latest news and updates:**  
<center>
  <a href="https://twitter.com/{{ site.twitter_username }}">
    <i class="fa fa-twitter fa-3x"></i> Twitter
  </a><br>
  <a href="{{ site.github.repository_url }}">
    <i class="fa fa-github fa-3x"></i> GitHub
  </a>
</center>

<p>&nbsp;</p>
**Check out the BacArena publication:**  
>Eugen Bauer\*, Johannes Zimmermann\*, Federico Baldini, Ines Thiele, Christoph Kaleta  
>**_BacArena: Individual-based metabolic modeling of heterogeneous microbes in complex communities_**
>PLOS Computational Biology (2017) 13,5 [doi:10.1371/journal.pcbi.1005544](https://doi.org/10.1371/journal.pcbi.1005544)  


<p>&nbsp;</p><p>&nbsp;</p>
<center><i class="fa fa-laptop fa-5x" aria-hidden="true"></i></center>
<center><h1>Installation and first steps</h1></center>
<p>&nbsp;</p>
BacArena is written in R language and can be installed easily via The Comprehensive R Archive Network ([CRAN](https://cran.r-project.org/package=BacArena)):
```r
install.packages('BacArena')
library('BacArena')
openArena()
```

<p>&nbsp;</p>
**Installing the development version**  
The [CRAN](https://cran.r-project.org/package=BacArena) version of BacArena is updated less frequently.
If you want to use the latest features and bugfixes, then try out the developtment version:
```r
install.packages('devtools')
install.github("euba/bacarena")
library('BacArena')
```

<p>&nbsp;</p>
**Problems with SBML**  
Currently, sybilSBML is not available on CRAN. 
You can install it manually from a linux terminal by:
```
wget https://www.cs.hhu.de/fileadmin/redaktion/Oeffentliche_Medien/Fakultaeten/Mathematisch-Naturwissenschaftliche_Fakultaet/Informatik/Bioinformatik/sybilSBML_3.0.5.tar.gz
R CMD INSTALL  sybilSBML_3.0.5.tar.gz
```


<p>&nbsp;</p><p>&nbsp;</p>
<center><i class="fa fa-info fa-5x" aria-hidden="true"></i></center>
<center><h1>Getting help</h1></center>
<p>&nbsp;</p>

Check out our [**Tutorial**](https://cran.r-project.org/web/packages/BacArena/vignettes/BacArena-Introduction.pdf) and [**Manual**](https://cran.r-project.org/web/packages/BacArena/BacArena.pdf)
- <a href="https://gist.github.com/jotech/22d46d901d5d63aeb58f007b9882e056">Doing a simple simulation using the E. coli model (iJO1366)</a>
- <a href="https://gist.github.com/jotech/8dd1e27b21ab70ecf2b2a56e5b70a2e0">Working with flux distributions and reaction activities</a>
- <a href="https://gist.github.com/jotech/bb28c3d59baeba4b9d7f115257916888">Analyzing bacterial interaction and cross-feeding patterns </a>
- <a href="https://gist.github.com/jotech/7434b56e462f6e9e90e5d99dc0994b61">Simple simulation without spatial component and disabled growth model </a>

<script src="https://gist.github.com/jotech/bb28c3d59baeba4b9d7f115257916888.js"></script>

<p>&nbsp;</p><p>&nbsp;</p>
<center><i class="fa fa-camera-retro fa-5x" aria-hidden="true"></i></center>
<center><h1>Pictures</h1></center>
<p>&nbsp;</p>

<center><img src="{{ site.url }}/img/bacarena.png" alt="Drawing" style="width: 300px;"/></center>
<center><img src="{{ site.url }}/img/bacarena_poa.png" alt="Drawing" style="width: 600px;"/></center>
<center><img src="{{ site.url }}/img/bacarena_sihumi1.png" alt="Drawing" style="width: 600px;"/></center>
<center><img src="{{ site.url }}/img/bacarena_sihumi2.png" alt="Drawing" style="width: 400px;"/></center>

[comment]: <> <script src="https://gist.github.com/parkr/c08ee0f2726fd0e3909d.js"> </script>
