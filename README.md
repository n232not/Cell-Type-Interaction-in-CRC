# Cell-Type-Interaction-in-CRC

This code uses single cell RNA data from [this study](https://www.sciencedirect.com/science/article/pii/S0092867421009454) to identify patterns of cell type interactions in cancer.

Paper.pdf contains the final paper I submitted to the collegeboard for AP Research.

For a basic overview, I identified 78 different cell types using the single cell expression data of 35 tumors and cell type markers provided in the same study. I trained XGBoot trees on the normalized relative proportions of cell types in each tumor and then performing SHAP analysis (a technique that can explain why a machine learning models makes the prediction it does) to identify the relationship patterns between different cell types. Tho none of the results can prove any causal interactions, they could be useful in guiding future research in evolutionary game theory.

Have fun!
