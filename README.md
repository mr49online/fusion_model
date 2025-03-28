# fusion_model
**1. Training & Validation Metrics Over Epochs**
Tracks the loss and accuracy of GCN+MPNN during training. Early stopping helps prevent overfitting.

**2. PCA Visualization of Embeddings**

Shows the PCA-based projection of graph embeddings from GCN and MPNN, highlighting clear separation between classes.

**3. Execution Time for All Pipeline Steps**

Breakdown of time taken for each major step including GNN training, model training, and ablation experiments. Experiments were conducted on CPU only. _(7_execution_time.png)_

**4. Confusion Matrix – Fusion Model (Logistic Regression)**

Shows classification performance of the logistic regression-based fusion model.

**5. Confusion Matrix – Fusion Model (SVM)**

An additional experiment using SVM-based fusion (not included in original paper).

**6. Bar Plot – Ablation Study Results**

Compares LR and SVM accuracy under different component removals.

**7. Heatmap – Impact of Ablation**

Shows how removing different components affects LR/SVM accuracy and ROC-AUC scores.

⚠️ Note: At the time of paper submission, only Logistic Regression was used as the fusion model. SVM results are added as an extended study post-submission.

