# Protein-Tertiary-Structure
One of the most important topics of research in the field of molecular biology is the 3D reconstruction of macromolecules like proteins. The study of protein tertiary structure contributes to protein function and also used for medicine design and drug discovery. The prediction of protein structure is one of the most challenging tasks in bioinformatics. This caused in recent years soft computing technologies as the best possibilities to solve this type of tasks.
To estimate residue size for each protein we used the following supervised learning algorithms:
* artificial neural network,
* random forest,
* multi-layer perceptron,
* gradient boosting.

<p align='center'>
<img src='https://user-images.githubusercontent.com/45270023/219205152-d6209d6d-e8b8-403b-9c20-3390dd4ae54e.jpg'/>
</p>

<div align='center'>

| Model            | MAE      | RMSE     | R2 Score |
|------------------|----------|----------|----------|
| RandomForest     | 0.466395 | 0.641751 | 0.588156 |
| GradientBoosting | 0.485399 | 0.659230 | 0.565416 |
| MLP              | 0.488006 | 0.667914 | 0.553890 |
| ANN              | 0.505709 | 0.689411 | 0.524713 |

</div>

We achieved such results while evaluating the models. Overall, the scores are moderate. The dataset does not have much characteristics for developing machine learning models with high usefullness. The top regressor with highest performance was the **random forest**. Estimating residue size with this dataset is possible, yet still not accurate.
