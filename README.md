# CaptainCook4D: A Dataset for Understanding Errors in Procedural Activities

<div align=center>
  <a src="https://img.shields.io/badge/project-website-green" href="https://captaincook4d.github.io/captain-cook/">
    <img src="https://img.shields.io/badge/project-website-green">
  </a>
  <a src="https://img.shields.io/badge/paper-arxiv-red" href="https://arxiv.org/abs/2312.14556">
    <img src="https://img.shields.io/badge/paper-arxiv-red">
  </a>
  <a src="https://img.shields.io/badge/bibtex-citation-blue" href="https://captaincook4d.github.io/captain-cook/#citation">
    <img src="https://img.shields.io/badge/bibtex-citation-blue">
  </a> 
</div>

<p align="center">
  (This page is under continuous update and construction.)
</p>

----

## Update

**Dec 22nd 2024:** Released all the checkpoints for error recognition models.

**Oct 31st 2024:** Released final code for baselines and features used for training the models.

**Sep 26th 2024:** Our paper was accepted into NeurIPS 2024 with the scores: 8,8,7.

**Oct 30th 2024:** Release of updated final code for baselines on (a) **Error Recognition** - (Supervised, Zero-Shot) (b) **Multi-Step Localization**

**Aug 2024:** Released extracted features for the dataset using Video Recognition Models.

**July 2024:** Release of code for baselines (a) **Error Recognition** (b) **Multi-Step Localization**

**Dec 2023:** Released dataset version 1.0

----

<div align="center">
    <h3>Overview</h3>
</div> 

![Overview](https://raw.githubusercontent.com/CaptainCook4D/captain-cook/main/static/images/TitleImage.svg)

----

<div align="center">
    <h3>Abstract</h3>
</div> 

Following step-by-step procedures is an essential component of various activities carried out by individuals in their everyday lives.
These procedures serve as a guiding framework that helps achieve goals efficiently, whether assembling furniture or preparing a recipe.
However, the complexity and duration of procedural activities inherently increase the likelihood of making errors.
Understanding such procedural activities from a sequence of frames is a challenging task that demands an accurate
interpretation of visual information and an ability to reason about the structure of the activity.
To this end, we collected a new egocentric 4D dataset, Captain Cook, comprising 384 recordings (94.5 hrs) of people performing recipes in real kitchen environments.
This dataset consists of two distinct activity types: one in which participants adhere to the provided recipe instructions and another where they deviate and induce errors.
We provide 5.3K step annotations and 10K fine-grained action annotations and benchmark it on the following tasks: supervised error recognition, multi-step localization and procedure learning.

----

<div align="center">
    <h3>Normal & Error Steps</h3>
</div>


https://github.com/user-attachments/assets/d366002a-1832-48f7-8bc4-2a7774d4d4ef


<p class="subtitle has-text-centered">
<span class="recipe">Technique Error:</span>
<span class="recipe_description">In the recipe <span class="recipe"> <b>butter corn cup</b> </span>
  the first two video snippets exhibit the outcome of correctly following the instruction
  <span class="recipe"> <b><u>Mix the contents of the bowl well</u></b> </span> without any spillage,
  whereas the subsequent three snippets display the result of inducing errors by spilling out corn from the bowl
  while mixing.
</span>
</p>


https://github.com/user-attachments/assets/c65c4089-1421-4494-b1ba-cbe072a71fa6


<p class="subtitle has-text-centered">
<span class="recipe">Measurement Error:</span>
<span class="recipe_description">In the recipe <span class="recipe"> <b>scrambled eggs</b> </span>
  the first two video snippets exhibit the outcome of correctly following the instruction
  <span class="recipe"> <b><u>Peel 2 garlic cloves</u></b> </span>,
  whereas the subsequent three snippets display the result when a different number of garlic cloves
  (4, 1, and 1 respectively) are peeled instead of the intended 2 cloves.
</span>
</p>



https://github.com/user-attachments/assets/9a6b7470-5284-49fe-9616-0e3458ded6b4


<p class="subtitle has-text-centered">
<span class="recipe">Order Error:</span>
<span class="recipe_description">In the recipe <span class="recipe"> <b>spicy tuna avacado wraps</b> </span>
  the first two video snippets exhibit the outcome of correctly following the instruction
  <span class="recipe"> <b><u>Top lettuce leaves with tuna mixture</u></b> </span>,
  whereas the subsequent three snippets display the result when an incorrect order is
  followed where avacado is added after topping the leaves with the mixture.
</span>
</p>



https://github.com/user-attachments/assets/b5bdac1c-522b-4801-a864-55c28039a3c3


<p class="subtitle has-text-centered">
<span class="recipe">Preparation Error:</span>
<span class="recipe_description">In the recipe <span class="recipe"> <b>mug cake</b> </span>
  the first two video snippets exhibit the outcome of correctly following the instruction
  <span class="recipe"> <b><u>Whisk batter</u></b> </span>, while the remaining snippets depict incorrect usage
  of utensils such as a spoon, tablespoon, and hand to perform the same task.
</span>
</p>


https://github.com/user-attachments/assets/4e45a905-4ad5-4818-bc0e-0d76aa3ed740


<p class="subtitle has-text-centered">
<span class="recipe">Technique Error:</span>
<span class="recipe_description">In the recipe <span class="recipe"> <b>cucumber raita</b> </span>
  the first two video snippets exhibit the outcome of correctly following the instruction
  <span class="recipe"> <b><u>Chop or grate the cucumber</u></b> </span>, while the next three frames
  on the right show the results when the cucumber is cut improperly, sliced vertically,
  and sliced horizontally, respectively.
</span>
</p>

----

<div align="center">
    <h3>4D Snippets</h3>
</div>


https://github.com/Error-Dataset/Error-Dataset/assets/130110495/d7a0f0d8-8ed2-4d37-ba0b-8b93a595a9c0


----

<div align="center">
    <h3>Task Graphs</h3>
</div>


You can find the task graphs for the following tasks in the dataset here: [Task Graphs](https://github.com/Error-Dataset/annotations)


https://github.com/user-attachments/assets/f32e37c6-adb9-4bd8-952b-7effa3de4b01


----

<div align="center">
    <h3>Annotation Overview</h3>
</div>


![Annotation Overview](https://raw.githubusercontent.com/CaptainCook4D/captain-cook/main/static/images/RecipeTimeline.svg)

----

<div align="center">
    <h3>Data Collection and Annotation Illustration</h3>
</div>


https://github.com/user-attachments/assets/87cae353-536b-48ad-942e-5eeb7c725089


----

<div align="center">
    <h3>Error Categories</h3>
</div>



![Error Categories](https://raw.githubusercontent.com/CaptainCook4D/captain-cook/main/static/images/ErrorCategories.svg)

----


<div align="center">
    <h3>Baselines</h3>
</div>



<div align="center">
    <h5>Supervised Error Recognition</h5>
</div>

![Supervised Error Recognition](https://raw.githubusercontent.com/CaptainCook4D/captain-cook/main/static/images/ErrorRecognitionBaseline.svg)


<div align="center">
    <h5>Zero-Shot Error Recognition</h5>
</div>

![Zero Shot Error Recognition](https://raw.githubusercontent.com/CaptainCook4D/captain-cook/main/static/images/ZeroShotErrorRecognition.svg)

<div align="center">
    <h5>Multi Step Localization</h5>
</div>

![Multi Step Localization](https://raw.githubusercontent.com/CaptainCook4D/captain-cook/main/static/images/MultiStepLocalizationQualitativeResults.svg)

----

<div>
    <h3>Data Collection System</h3>
</div>


- [Data Collection System](https://github.com/Error-Dataset/data-collection)


----


<div>
    <h3>Download Data</h3>
</div>


- [Downloader](https://github.com/CaptainCook4D/downloader)

----

<div>
    <h3>Annotations</h3>
</div>


- [Data Statistics](https://github.com/Error-Dataset/annotations)
- [Train/Test Splits](https://github.com/Error-Dataset/annotations)

----


<div>
    <h3>Features</h3>
</div>


- [Feature Extraction](https://github.com/CaptainCook4D/feature_extractors)

----


<div>
    <h3>Baselines</h3>
</div>


- [Supervised Error Recognition](https://github.com/CaptainCook4D/error_recognition)
- [Zero Shot Error Recognition](https://github.com/CaptainCook4D/zero_shot_error_recognition)
- [Multi Step Localization](https://github.com/CaptainCook4D/multi_step_localization)

----

<div>
    <h2>Works that used CaptainCook4D</h2>
</div>


**Oct 2024:** [ProMQA: Question Answering Dataset for Multimodal Procedural Activity Understanding
](https://arxiv.org/abs/2410.22211)

**Jun 2024:** [Differentiable Task Graph Learning](https://arxiv.org/abs/2406.01486)

----

<div>
    <h3>License & Consent</h3>
</div>

Our dataset is licensed under the Apache license 2.0: [License](https://www.apache.org/licenses/LICENSE-2.0).

Our dataset is approved by the Institutional Review Board (IRB) at the University of Florida: [IRB Approval](https://utdallas.box.com/s/mplxyvsowyay1lr048bur9habarjgkt9) 

All participants provided written consent for the data collection: [Consent](https://utdallas.box.com/s/2qkvsgrn8gfs66o8ha8hnee011t03yl2)

----
## NeurIPS Scores

![PreRebuttalScores](https://github.com/user-attachments/assets/2131cf50-07cf-4d7d-b451-4beb6576fc22)

----

## Citation

```python

@inproceedings{NEURIPS2024_f4a04396,
 author = {Peddi, Rohith and Arya, Shivvrat and Challa, Bharath and Pallapothula, Likhitha and Vyas, Akshay and Gouripeddi, Bhavya and Zhang, Qifan and Wang, Jikai and Komaragiri, Vasundhara and Ragan, Eric and Ruozzi, Nicholas and Xiang, Yu and Gogate, Vibhav},
 booktitle = {Advances in Neural Information Processing Systems},
 editor = {A. Globerson and L. Mackey and D. Belgrave and A. Fan and U. Paquet and J. Tomczak and C. Zhang},
 pages = {135626--135679},
 publisher = {Curran Associates, Inc.},
 title = {CaptainCook4D: A Dataset for Understanding Errors in Procedural Activities},
 url = {https://proceedings.neurips.cc/paper_files/paper/2024/file/f4a04396c2ed1342a5d8d05e94cb6101-Paper-Datasets_and_Benchmarks_Track.pdf},
 volume = {37},
 year = {2024}
}

```


