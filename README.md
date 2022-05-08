# Cell-Type-Interaction-in-CRC

This code uses single cell RNA data from [this study](https://www.sciencedirect.com/science/article/pii/S0092867421009454) to identify patterns of cell type interactions in cancer.

The file named paper.pdf is the final paper i submitted to the collegeboard for AP Research.

For a basic overview, I basically identified 78 different cell types using the single cell expression data of 35 tumors and cell type markers provided in the same study. I experimented around with data by using machine learning models (XGboost) on the relative proportions of cell types in each tumor and then performing SHAP analysis ( atechnique that can explain why amachine learning models makes the prediction it does) to figure out how these different cell types interact nonlinearly. I found some pretty cool trend that I identified in the results of section of my paper.

Have fun!
