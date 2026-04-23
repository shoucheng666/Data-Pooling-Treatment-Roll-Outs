# Data-Pooling-Treatment-Roll-Outs
This is the code files for paper: **Synthesizing Evidence: Data-Pooling as a Tool for Treatment Selection in Online Experiments**.
The provided code includes experiments on synthetic data as well as two public experimental datasets, i.e, Criteo dataset and Expedia dataset.
The experiments on synthetic data are located in the Synthetic Experiments folder.


# Synthetic Experiments
1. **Scenario 1 - no feature.ipynb**: This notebook contains the validation code for Scenario 1, which assumes a linear specification, non-overlapping experiments, and excludes feature information.

   **Scenario 1 - with feature.ipynb**: This notebook contains the validation code for Scenario 1, which assumes a linear specification, non-overlapping experiments, and includes feature information.
2. **Scenario 2.ipynb**: This notebook contains the validation code for Scenario 2, which assumes a non-linear specification and non-overlapping experiments.
3. **Scenario 3.ipynb**: This notebook contains the validation code for Scenario 3, which assumes a linear specification and overlapping experiments.

   **Scenario 3-for DM.ipynb**: This notebook contains the validation code for Scenario 3, which assumes a linear specification with overlapping experiments, while using the Difference-in-Means (DM) method for estimation.
4. **Scenario 4.ipynb**: This notebook contains the validation code for Scenario 4, which assumes a non-linear specification and overlapping experiments.

   **Scenario 4-for DM.ipynb**: This notebook contains the validation code for Scenario 4, which assumes a non-linear specification and overlapping experiments, while using the Difference-in-Means (DM) method for estimation..
5. **Appendix D_sigmoid.ipynb**: This notebook contains the validation code for Appendix D, where the underlying policy ATEs are assumed to be sigmoid, to evaluate the robustness of our method.
6. **Appendix E.1_non_linear.ipynb**: This notebook contains the validation code for Appendix E.1, where the underlying policy ATEs are assumed to be generilised non-linear, to show the limitation of our method.

   **Appendix E.2_with_capacity_constraint.ipynb**: This notebook contains the validation code for Appendix E.2, where the capacity constaint will be added when making roll-out decisions.
7. **Appendix F.1_variance_analysis_of_anchor.ipynb**: This notebook contains the validation code for Appendix F.1, where we show that the variance of the estimated anchor will decrease with the number of experiments under the overlapping setting.

   **Appendix F.2_compare_with_BH.ipynb**: This notebook contains the validation code for Appendix F.2, where we compare our method with Benjamini–Hochberg procedure.
   
# Criteo.ipynb
The Criteo dataset can be accessed via the link. (https://ailab.criteo.com/criteo-uplift-prediction-dataset/).
The notebook provides a detailed walkthrough on how to use the dataset to validate our method.

# Expedia.ipynb
The Expedia dataset can be accessed via the link. (www.kaggle.com/c/expedia-personalized-sort/data).
The notebook provides a detailed walkthrough on how to use the dataset to validate our method.
