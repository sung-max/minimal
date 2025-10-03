---
layout: default
---

<p>&nbsp;</p>
## About
I am a postdoc at Stanford CS working with Profs. Tatsu Hashimoto, Percy Liang, and James Zou.
I did my PhD at MIT, where I was advised by Prof. Aleksander Mądry. Prior to that,
I studied Computer Science at Cornell, where I was fortunate to work with Prof. Ramin Zabih and Prof. Bobby Kleinberg.

I'm broadly interested in the science of machine learning.

Recently, my interests have been in understanding and improving machine learning methodology
through the *lens of data*:
 - How do we *attribute* model predictions back to training data? (e.g., see our recent ICML tutorial [[video](https://icml.cc/virtual/2024/tutorial/35228)] [[notes](https://ml-data-tutorial.org/)])
 - How do we *select* (and optimize) the right data for a given task?
 - Can we derive insights about ML phenomena (e.g., scaling laws, emergence, optimization dynamics) through this lens?

<p>&nbsp;</p>

## Research

<style>
.pub-toggle { margin: 0.25rem 0 0.75rem 0; }
.pub-toggle a { cursor: pointer; text-decoration: none; color: #0366d6; }
.pub-toggle a.active { font-weight: bold; text-decoration: underline; }
.pub-item { margin-bottom: 1rem; }
</style>

<div class="pub-toggle">
<a href="#" data-view="selected" class="active">Selected</a> | <a href="#" data-view="all">All</a>
</div>

<div id="pub-list">


<div class="pub-item" data-selected="true" markdown="1">
**Attribute-to-Delete: Machine Unlearning via Datamodel Matching**<br>
Kristian Georgiev\*, Roy Rinberg\*, <u>Sung Min Park*</u>, Shivam Garg\*, Andrew Ilyas, Aleksander Mądry, Seth Neel <br>
ICLR 2025<br>
[[<u>arxiv</u>]](https://arxiv.org/abs/2410.23232) [[<u>blog</u>](https://t.co/QVgG2FlNmB)]
</div>

<div class="pub-item" data-selected="false" markdown="1">
**The Journey, Not the Destination: How Data Guides Diffusion Models**<br>
Kristian Georgiev\*, Josh Vendrow\*, Hadi Salman, <u>Sung Min Park</u>, Aleksander Mądry <br>
[[<u>arxiv</u>]](https://arxiv.org/abs/2312.06205)
</div>

<div class="pub-item" data-selected="true" markdown="1">
**TRAK: Attributing Model Behavior at Scale**<br>
<u>Sung Min Park*</u>, Kristian Georgiev\*, Andrew Ilyas\*, Guillaume Leclerc, Aleksander Mądry <br>
ICML 2023 (Oral presentation)<br>
[[<u>arxiv</u>]](https://arxiv.org/abs/2303.14186) [[<u>blog</u>](https://gradientscience.org/trak/)][[<u>code</u>](https://github.com/MadryLab/trak)]
[[<u>website</u>]](https://trak.csail.mit.edu/)[[<u>talk</u>](https://icml.cc/virtual/2023/oral/25526)]
</div>

<div class="pub-item" data-selected="true" markdown="1">
**ModelDiff: A Framework for Comparing Learning Algorithms**<br>
Harshay Shah\*, <u>Sung Min Park*</u>, Andrew Ilyas\*, Aleksander Mądry <br>
ICML 2023<br>
[[<u>arxiv</u>]](https://arxiv.org/abs/2211.12491) [[<u>blog</u>](https://gradientscience.org/modeldiff/)][[<u>code</u>](https://github.com/MadryLab/modeldiff)]
</div>

<div class="pub-item" data-selected="false" markdown="1">
**FFCV: Accelerating Training by Removing Data Bottlenecks**<br>
Guillaume Leclerc, Andrew Ilyas, Logan Engstrom, <u>Sung Min Park</u>, Hadi Salman, Aleksander Mądry <br>
CVPR 2023<br>
[[<u>code</u>]](https://github.com/libffcv/ffcv)
</div>

<div class="pub-item" data-selected="false" markdown="1">
**A Data-Based Perspective on Transfer Learning**<br>
Saachi Jain\*, Hadi Salman\*, Alaa Khaddaj\*, Eric Wong, <u>Sung Min Park</u>, Aleksander Mądry<br>
CVPR 2023<br>
[[<u>arxiv</u>]](https://arxiv.org/abs/2207.05739) [[<u>blog</u>](https://gradientscience.org/data-transfer/)]
</div>

<div class="pub-item" data-selected="true" markdown="1">
**Datamodels: Predicting Predictions from Training Data**<br>
Andrew Ilyas\*, <u>Sung Min Park*</u>, Logan Engstrom\*, Guillaume Leclerc, Aleksander Mądry<br>
ICML 2022<br>
[[<u>arxiv</u>]](https://arxiv.org/abs/2202.00622) [blog [<u>part 1</u>](https://gradientscience.org/datamodels-1/) [<u>part 2</u>](https://gradientscience.org/datamodels-2/)] [[<u>code</u>](https://github.com/MadryLab/datamodels)][[<u>data</u>]](https://github.com/MadryLab/datamodels-data)
</div>

<div class="pub-item" data-selected="false" markdown="1">
**On Distinctive Properties of Universal Perturbations**<br>
<u>Sung Min Park</u>, Kuo-An Wei, Kai Xiao, Jerry Li, Aleksander Mądry<br>
2021<br>
[[<u>arxiv</u>]](https://arxiv.org/abs/2112.15329)
</div>

<div class="pub-item" data-selected="false" markdown="1">
**Sparse PCA from Sparse Linear Regression**<br>
(α-β order) Guy Bresler, <u>Sung Min Park</u>, Madalina Persu<br>
NeurIPS 2018<br>
[[<u>arxiv</u>]](https://arxiv.org/abs/1811.10106) [[<u>poster</u>]](/assets/files/neurips_2018_poster.pdf) [[<u>code</u>]](https://github.com/sung-max/SPCAvSLR)
</div>

<div class="pub-item" data-selected="false" markdown="1">
**Structured learning of sum-of-submodular higher order energy functions**<br>
Alexander Fix, Thorsten Joachims, <u>Sung Min Park</u>, Ramin Zabih<br>
ICCV 2013<br>
[[<u>pdf</u>]](/assets/files/submodular.pdf)
</div>

</div>

<script>
(function() {
function setView(view) {
var items = document.querySelectorAll('#pub-list .pub-item');
var toggleLinks = document.querySelectorAll('.pub-toggle a');
Array.prototype.forEach.call(toggleLinks, function(link){
if (link.getAttribute('data-view') === view) {
link.classList.add('active');
} else {
link.classList.remove('active');
}
});
Array.prototype.forEach.call(items, function(item){
var isSelected = item.getAttribute('data-selected') === 'true';
if (view === 'selected') {
item.style.display = isSelected ? '' : 'none';
} else {
item.style.display = '';
}
});
if (history && history.replaceState) {
history.replaceState(null, '', view === 'all' ? '#all' : '#selected');
} else {
location.hash = view === 'all' ? '#all' : '#selected';
}
}
document.addEventListener('DOMContentLoaded', function() {
var defaultView = (location.hash === '#all') ? 'all' : 'selected';
setView(defaultView);
Array.prototype.forEach.call(document.querySelectorAll('.pub-toggle a'), function(link){
link.addEventListener('click', function(e){
e.preventDefault();
setView(this.getAttribute('data-view'));
});
});
});
})();
</script>


<p>&nbsp;</p>
## Theses & Misc

**Machine Learning through the Lens of Data**\
MIT, PhD thesis, 2024\
[[<u>link</u>]](https://dspace.mit.edu/handle/1721.1/159360)

**On the Equivalence of Sparse Statistical Problems**\
MIT, SM thesis, 2016\
[[<u>pdf</u>]](/assets/files/sm_thesis.pdf)

**Region Detection and Geometry Prediction**\
Patent from work during Summer 2020 internship at Waymo\
[[<u>pdf</u>]](/assets/files/waymo_patent.pdf)

**Fourier Theoretic Probabilistic Inference over Permutations**\
Cornell, Spring 2014\
[[<u>pdf</u>]](/assets/files/fourier.pdf)

**Analysis of pipage method for k-max coverage**\
Cornell, Fall 2012\
[[<u>pdf</u>]](/assets/files/max_coverage.pdf)

<p>&nbsp;</p>
## Talks

* **Mar 2024** Stanford ML lunch
* **Jul 2023** [ICML Oral](https://icml.cc/virtual/2023/oral/25526)
* **May 2023** [LIDS & Stats Tea](https://lids.mit.edu/news-and-events/events/trak-attributing-model-behavior-scale)
* **May 2023** MIT MLTea
* **Apr 2023** [ML Collective Reading group](https://mlcollective.org/dlct/)
* **Feb 2023** [MIT LIDS Student Conference](https://lidsconf.mit.edu/2023/program.html)
* **Aug 2022** [UMN ML Seminar](https://sites.google.com/umn.edu/machine-learning)
* **Feb 2022** [LIDS & Stats Tea](https://lids.mit.edu/news-and-events/lids-stats-tea)
* **Jan 2022** [MIT LIDS Student Conference](https://lidsconf.mit.edu/2022/program.html)

<p>&nbsp;</p>

## Bio
Earlier in grad school, I worked on understanding statistical-computational tradeoffs in high-dimensional statistics with Prof. Guy Bresler for my SM thesis. During my PhD, I was partially supported by the MIT Akamai Presidential Fellowship and the Samsung Scholarship.

From 2016-18, I took a leave from grad school to serve in the Republic of Korea Army in the top signals intelligence unit as a researcher.

I have interned at Waymo, Dropbox, and Google.

<p>&nbsp;</p>


## Personal

I grew up between the Bay Area, Seoul, and Singapore, where I attended [SAS](https://www.sas.edu.sg/).

In my free time, I enjoy working out, playing basketball, [rowing](/assets/img/rowing.jpg), watching the NBA (nuggets!), watching movies, and learning [theoretical physics](https://sung-max.github.io/learning-qft/) and math.
<p>&nbsp;</p>
