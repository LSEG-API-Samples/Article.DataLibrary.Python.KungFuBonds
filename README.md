To see Jupyter Notebook file with plot and graph output, [Click here to view the notebook via Jupyter Notebook viewer](https://nbviewer.org/github/Refinitiv-API-Samples/Article.RDP.Python.KungFuBonds/blob/main/kung-fu-bonds-data-library-search.ipynb)
# Searching for KungFu Bonds (Chinese-issued U.S. dollars bonds) with the Data Library - Search function
DDue to Greater Bay Area (GBA) has a lot of population (86M) and huge number of GDP ($1.6T), there’s a huge potential of this market with investment opportunities across multiple asset classes and propositions.

In this article, we’re focusing on Kung Fu Bonds (The bond issued by a Chinese entity in USD currency) as we notice that their market has been growing. Hence, the Data Library is being used to create the solution to identify, aggregate and visualize KungFu bonds.

## Pre-requisites:
The code can be run on Refinitiv Codebook or Jupyter Notebook that has the Data library installed and ready to be used. To run examples in this article, I'll be using my local Jupyter Notebook.
    -  In case you’re running the Jupyter Notebook in your own environment (not using Codebook),
        -  The Access Credential is required to use the Data Library. For more detail, please check page Data Library - Access Credentials, or it will be taken from Workspace application automatically.
        -  Workspace Desktop should be running and being logged-in in the same machine where the code is running
        -  Required python libraries:
            -  lseg-data==2.0.0
            -  pandas==2.2.2
            -  plotly==5.22.0
            -  datetime
            -  dateutil
You may contact your account representative to help you to access LSEG workspace.

## Visualization output
1) TRBC Pie
2) Bond Grade Pie
3) Issued amount last 12 months
4) Redem amount in 10 years
5) Newly issued bonds last 3 months
6) Price top 10
7) Yield top 10
8) Yield last 10
