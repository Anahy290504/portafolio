# Anahy Santiago Arguello
# Discrete Mathematics | Machine Learning

#### Technical Skills: 
-Languages: Python, C/C++

-ML/DL: PyTorch, TensorFlow, scikit-learn, CatBoost

-Data Analysis: NumPy, Pandas, SciPy, Matplotlib, Seaborn

-Other: Git, Jupyter, LaTeX

## About me

I am a mathematician and data scientist with a strong background in discrete mathematics, graph theory, and machine learning. After completing my Ph.D. in Mathematics at UNAM and postdoctoral research in Leipzig, I transitioned into applied data science, where I work on projects that bridge theoretical foundations with real-world applications.

I am passionate about:

-Designing machine learning models for real-world problems.

-Exploring the intersection of mathematics, data science, and biology.

-Building efficient algorithms with both theoretical rigor and practical usability.

## Education
-Ph.D. in Mathematics | UNAM- IMATE Mexico City (_December 2018_)

-Master’s degree on Mathematics| UNAM-IMATE Mexico City (_July 2014_)

-Bachelor on Mathematics | UNAM-FC Mexico City (_July 2012_)

## Work Experience
**Data Science Consultant at Constructor | Best Secret Data Scientist (_November 2024_)**
- Collaborated with the Best Secret Data Science team to develop a CatBoost-based machine learning model to optimize packaging in e-commerce logistics.
- Engineered new product features, improving model accuracy from 0.5 to 0.7.
- Provided recommendations for collecting more relevant data, further enhancing model performance

**Postdoctoral Researcher at University of Leipzig and ScaDS.AI Dresden/Leipzig (_May 2023 - June 2024_)**
- Advanced the theoretical foundations of the Consensus Segmentation problem by analyzing potential properties and their impact on segmentation solutions.
- Disproved a conjecture from the paper Weighted Consensus Segmentations (Computation, 2021; 9(2):17, DOI: 10.3390/computation9020017).

**Postdoctoral Researche at University of Leipzig and Mewedo (_February 2022 - April 2023_)**
- Designed a model to assess student skills and match candidates to job offers, collaborating with cross-disciplinary experts.
- Developed a tailored proficiency metric based on five factors, delivering more accurate job fit assessments.
- Outperformed standard evaluations by capturing job-specific competencies and providing deeper insights into candidate suitability

**Postdoctoral Researcher at  University of Leipzig (_November 2019 - October 2021_)**
- Designed an algorithm to find Hamiltonian cycles (tours) in power graphs, with applications in network optimization and graph-based machine learning models.
- Defined and explored the properties of a connectivity concept for directed hypergraphs, with applications in network analysis and multi-relational data modeling

## Projects
## Optimizing Packaging with Machine Learning: A Case Study
In a recent project within the luxury fashion retail sector, a data science team set out to enhance the package selection process through predictive modeling. The goal was to support packers in choosing the optimal box size swiftly and accurately, thereby improving both the speed and consistency of packing operations. This work was carried out in collaboration with Simon Püschel.

<p align="center">
  <img src="/Pictures/Packing.jpeg" width=30% height=30%>
</p>

### Project Overview: Challenges and Solutions
The existing package selection process relied heavily on experienced packers who determined box sizes based on the types and quantities of items in each order. However, this approach could be time-consuming, particularly for seasonal workers without intuitive expertise. The project aimed to develop a machine learning model capable of quickly and reliably predicting the best package size for each order. One of the main challenges was handling eleven highly imbalanced classes.

Due to the absence of exact volume and weight data for individual items, the team devised methods to estimate these values. By analyzing single-item orders, they derived average volumes for various product categories, which helped feed crucial volume estimates into the model. Similarly, they calculated average weights across categories to serve as reference points, supporting accurate package size predictions.

To address item flexibility—a factor that influences packing decisions—the team implemented a basic classification system. Items with clear identifiers were tagged as “soft” or “hard.” For ambiguous cases, a secondary model was used to analyze product names and assign classifications based on learned patterns. The final model used essential product data such as volume, weight, and quantity to improve prediction accuracy.

### Model Selection and Performance
The team evaluated several machine learning models to identify the most effective approach. Gradient boosting algorithms achieved the highest accuracy at 64%, outperforming Random Forest and Neural Networks. To further enhance prediction performance, the problem was also reframed as a regression task. Ensemble learning techniques were introduced, and a variety of model combinations were tested to refine the results.

### Future Enhancements
Although the initial outcomes are promising, there are several potential improvements on the horizon. Creating a more granular product categorization could help the model capture subtle differences in item characteristics. Incorporating actual product weights would enhance precision, and testing the model in a live packing environment would provide real-world feedback for further optimization. This project has laid a strong foundation for a more efficient packaging process, and as refinement continues, predictive modeling is expected to play an increasingly vital role in optimizing packing operations.

[![View Code](https://img.shields.io/badge/View_Code-GitHub-blue)](https://github.com/Anahy290504/Optimizing_Packaging_ML/tree/main)



## Talks and Lectures
-Autocatalytic systems - 18th Bioinformatik Herbstseminar (2022)

-Sistemas Autocatalíticos - LVI Congreso de la Sociedad Matemática Mexicana (2021)

-Whitney’s connectivity inequalities for directed hypergraphs - TBI, Winterseminar (2020)

-Hamiltonian Cycles in normal Cayley graphs - CID (2017)

## Publications
1. Core Potentials: The Consensus Segmentation Conjecture., Math.Comput.Sci.18, 19 (2024)., https://doi.org/10.1007/s11786-024-00593-y, with G.E. Scholz and P.F. Stadler.
2. Hamiltonicity in power graphs of a class of abelian groups, Journal of Algebraic Combinatorics (2022), DOI: 10.1007/s10801-022-01172-9, with J.J. Montellano Ballesteros and P. F. Stadler.
3.  Whitney’s Connectivity Inequalities for Directed Hypergraphs., The Art of Discrete and Applied Mathematics (2020), https://doi.org/10.26493/2590-9770.1380.1c9, with Peter F. Stadler.
4.  Hamiltonian normal Cayley graphs, Discussiones Mathematicae Graph Theory 39(2) (2019), DOI: 10.7151/dmgt.2214, with J.J Montellano Ballesteros.
5.  Hamiltonian Cycles in Normal Cayley Graphs, Graphs and Combinatorics 35,1707–1714 (2019)., https://doi.org/10.1007/s00373-019-02090-7 with J.J Montellano Ballesteros.
