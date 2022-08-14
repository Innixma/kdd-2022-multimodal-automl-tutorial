Welcome to our [KDD'22](https://kdd.org/kdd2022/) Tutorial, "Multimodal AutoML for Image, Text and Tabular Data".

##  Tutorial Date, Time, Location
- **Date**: August 14th, 2022
- **Time**: Sun 9:00 am - 12:00 pm EST
- **Location**: Room 204B, Walter E. Washington Convention Center


## Tutorial Abstract

Automated machine learning (AutoML) offers the promise of translating raw data into accurate predictions without the need for significant human effort, expertise, and manual experimentation. In this lecture-style tutorial, we demonstrate fundamental techniques that powers up *multimodal* AutoML. Different from most AutoML systems that focus on solving tabular tasks that contain categorical and numerical features, we consider supervised learning tasks on various types of data including tabular features, text, and image, as well as their combinations. Rather than technical descriptions of how individual ML models work, we emphasize how to best use models within an overall ML pipeline that takes in raw training data and outputs predictions for test data.  

A major focus of our tutorial is on automatically building and training deep learning models, which are powerful yet cumbersome to manage manually. Hardly any educational material describes their successful automation. Each topic covered in the tutorial is  accompanied by a hands-on Jupyter notebook that implements best practices (which will be available on GitHub before and after the tutorial). Most of the code is adopted from [AutoGluon](https://auto.gluon.ai/), a recent open-source AutoML toolkit that is both state-of-the-art and easy-to-use.

## Tutorial Outline and Materials

Slides is available for preview: [link](https://docs.google.com/presentation/d/10pmrQha7Jr-1sXebG5rPOq4qTPXqeIj-/edit?usp=sharing&ouid=117434028345007023633&rtpof=true&sd=true).

1. Tabular AutoML
    - AutoML Basics: Discussion of core AutoML principles
    - History of competition ML and how it influenced the design of modern AutoML systems
    - Discussion of model combination strategies (stacking, bagging, model aggregation)
    - Constraint satisfaction and engineering for a performance envelope (accuracy, speed, compute resources)
    - Benchmark comparisons showcasing the advancement of AutoML systems in recent years both compared to earlier AutoML systems and human data scientists (4 AutoML frameworks, 104 OpenML datasets, 10 Kaggle datasets)
2. Multimodal AutoML
    - Real-world multimodal problems (life beyond captioning images)
    - Foundational models for image and text
    - Fusion techniques and other training tricks
    - Model distillation
    - Parameter-efficient finetuning
3. Advanced Topics
    - Dependent random variables (e.g., time series)
    - Exploratory data analysis (e.g., detecting distribution shift)
    - Explainability and fairness (e.g., SHAP)

## Short Bio of Lecturers

**[Nick Erickson](https://github.com/Innixma)** is a Senior Software Development Engineer at Amazon AI. He obtained his master's degree in Computer Science and Engineering from the University of Minnesota Twin Cities. He is the co-author and lead developer of the open-source AutoML framework AutoGluon. Starting as a personal competition ML toolkit in 2018, Nick continually expanded the capabilities of AutoGluon and joined Amazon AI in 2019 to open-source the project and work full time on advancing the state-of-the-art in AutoML.

**[Xingjian Shi](https://sxjscience.github.io/)** is a Senior Applied Scientist at Amazon AI. He obtained his Ph.D. in Computer Science and Engineering from the Hong Kong University of Science and Technology (HKUST). He has conducted research on recurrent neural network, graph neural network, Bayesian deep learning, and computer vision, with publications in top venues including NeurIPS, ICCV, WWW, AAAI, JMLR, etc. His work on deep learning for precipitation nowcasting has been cited over 1,000 times.

**[James Sharpnack](https://jsharpna.github.io/)** is a Senior Applied Scientist in Amazon AI.  He received his Ph.D. from Carnegie Mellon University in Statistics and Machine Learning.  Before joining Amazon, he was an Associate Professor in the UC Davis Statistics Department.  His research lies at the intersection of statistics and machine learning; it spans the topics of graph trend filtering, anomaly detection, recommender systems and bandits, non-parametric statistical inference, epidemiology, and transportation science.

## Cite our work
If you find our work useful, please cite our work
- KDD 2022 Tutorial (Multimodal AutoML for Image, Text and Tabular Data)
```
@inproceedings{erickson2022kddautoml,
  title={Multimodal AutoML for Image, Text and Tabular Data},
  author={Erickson, Nick and Shi, Xingjian and Sharpnack, James and Smola, Alex},
  booktitle={Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery \& Data Mining},
  pages={1--2},
  year={2022}
}
```
