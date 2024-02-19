# CaptainCook4D: A dataset for understanding errors in procedural activities

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

----

https://github.com/Error-Dataset/Error-Dataset/assets/130110495/d74392a3-1aea-43b4-a58f-a1c2375928be

----

## Abstract
Following step-by-step procedures is an essential component of various activities carried out by individuals in their everyday lives.
These procedures serve as a guiding framework that helps achieve goals efficiently, whether assembling furniture or preparing a recipe.
However, the complexity and duration of procedural activities inherently increase the likelihood of making errors.
Understanding such procedural activities from a sequence of frames is a challenging task that demands an accurate
interpretation of visual information and an ability to reason about the structure of the activity.
To this end, we collected a new egocentric 4D dataset, Captain Cook, comprising 384 recordings (94.5 hrs) of people performing recipes in real kitchen environments.
This dataset consists of two distinct activity types: one in which participants adhere to the provided recipe instructions and another where they deviate and induce errors.
We provide 5.3K step annotations and 10K fine-grained action annotations and benchmark it on the following tasks: supervised error recognition, multi-step localization and procedure learning.


https://github.com/Error-Dataset/Error-Dataset/assets/130110495/d7a0f0d8-8ed2-4d37-ba0b-8b93a595a9c0

----

## Error Synopsis

A structured synopsis of different types of errors and their short descriptions compiled from the annotations.
We classified common errors performed during a cooking activity into the following categories 
(1) Preparation Error, (2) Measurement Error, (3)  Technique Error, (4) Timing Error, (5) Temperature Error, (6) Missing Steps, and (7) Ordering Error.

![ErrorSynopsisWithoutBrackets](https://github.com/CaptainCook4D/CaptainCook4D/assets/130110495/394099a4-3c10-4b43-91c9-5dcae5bdef08)

----

## Citation

```python
@misc{peddi2023captaincook4d,
  title={{CaptainCook4D: A dataset for understanding errors in procedural activities}}, 
  author={Rohith Peddi and Shivvrat Arya and Bharath Challa and Likhitha Pallapothula and Akshay Vyas and Jikai Wang and Qifan Zhang and Vasundhara Komaragiri and Eric Ragan and Nicholas Ruozzi and Yu Xiang and Vibhav Gogate},
  year={2023},
  eprint={2312.14556},
  archivePrefix={arXiv},
  primaryClass={cs.CV}
}
```
----

## Code 

- [Data Collection System](https://github.com/Error-Dataset/data-collection)

## Annotations

- [Annotations](https://github.com/Error-Dataset/annotations)
- [Data Statistics](https://github.com/Error-Dataset/annotations)
- [Train/Test Splits](https://github.com/Error-Dataset/annotations)

## Additional Resources

- [Project Website](https://captaincook4d.github.io/captain-cook/) 
- [Paper](https://arxiv.org/abs/2312.14556) 
