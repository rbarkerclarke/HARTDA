# Robust Evaluation of Models Combining Deep-Learning and Engineered Topological Features for Impersonal Activity Recognition

The following repository accompanies the above manuscript. 

Authors:
Rowan Barker-Clarke
Nick Latina
Daniel Suh
Harshita Kumar
Jacob G Scott
Andrew Dhawan

Abstract: Although deep learning methods have achieved near-perfect accuracies (> 98%) for
individual-level human activity recognition (HAR), top-performing models fail to
generalize across individuals and unseen subjects. Further, the field faces a crisis in
reproducibility wherein performance gains in deep learning models often occur due to
random seed variance, as opposed to direct methodological improvements. To
address these dual challenges, we introduce a framework incorporating “shape-based”
features extracted using topological data analysis (TDA) from raw human activity data,
capturing invariant signal structures. Critically, we rigorously evaluate the performance
of this approach using subject identification, multiple seeds per trial, and distinguish
true architectural improvements from baseline variability. Across two publicly available
datasets (WISDM v.2 and WISDM-HARB), we demonstrate that integrating topological
features consistently improves accuracy compared to the baseline model structure. On
the 18-activity WISDM-HARB dataset, the best performing dual-input TDA-informed
model achieves a mean accuracy of 72.85% (range over folds: 67.28–79.67%),
outperforming the baseline with mean accuracy 70.7% (range over folds:
66.04–77.92%). Overall, our findings demonstrate that topological features enable
generalizable and improved performance in HAR, and demonstrate the value of
transparent multi-seed evaluation of model performance.


The pre-processing and cross-fold validation workflow is contained in HARTDA_Clean.ipynb 
The multi-seed, multi-model evaluation is in HARTDA_WISDM2025_ReproduceModels.ipynb
Figure generation is in SeedFigures notebook. 
