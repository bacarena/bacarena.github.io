---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#layout: home
layout: default
---
<link href="//maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">

<center><img src="{{ site.url }}/img/bacarena.png" alt="Drawing" style="width: 300px;"/></center>

# [](#header-1)Welcome to BacArena!

BacArena is an open source software for simulating cellular communities. 
It combines agent-based modeling, flux balance analysis, and statistical analysis.
BacArena is implemented in R and available on [CRAN](https://cran.r-project.org/package=BacArena)

{{ site.github.zip_url }}

<a class="btn btn-lg btn-success" href="#">
  <i class="fa fa-flag fa-2x pull-left"></i> BacArena<br>Version 4.7.0</a>


<i class="fa fa-camera-retro fa-5x"></i> 

Check out our [**Tutorial**](https://cran.r-project.org/web/packages/BacArena/vignettes/BacArena-Introduction.pdf) and [**Manual**](https://cran.r-project.org/web/packages/BacArena/BacArena.pdf)

<li>
  <a href="https://github.com/{{ site.github_username }}">
    <i class="fa fa-github"></i> GitHub
  </a>
</li>
<li>
  <a href="https://twitter.com/{{ site.twitter_username }}">
    <i class="fa fa-twitter"></i> Twitter
  </a>
</li>

Eugen Bauer*, Johannes Zimmermann*, Federico Baldini, Ines Thiele, Christoph Kaleta  
**_BacArena: Individual-based metabolic modeling of heterogeneous microbes in complex communities_**
PLOS Computational Biology (2017) 13,5 [10.1371/journal.pcbi.1005544](https://doi.org/10.1371/journal.pcbi.1005544)  



# [](#header-1)First steps

```r
install.packages('BacArena')
library('BacArena')
openArena()
```


[comment]: <> <script src="https://gist.github.com/parkr/c08ee0f2726fd0e3909d.js"> </script>
