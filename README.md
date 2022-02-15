# Searching for KungFu Bonds (Chinese-issued U.S. dollars bonds) with RDP Libraries - Search function
Due to Greater Bay Area (GBA) has a lot of population (86M) and huge number of GDP ($1.6T), there’s a huge potential of this market with investment opportunities across multiple asset classes and propositions. However, the ability to identify the exact investment opportunities and the consolidated source of GBA data isn’t directly accessed in Eikon Application/Refinitiv workspace yet

In this article, we’re focusing on Kung Fu Bonds (The bond issued by a Chinese entity in USD currency) as we notice that their market has been growing (there’re about 6,000 Active Kung Fu bonds). Hence, Refinitiv Data Platform (RDP) libraries are being used to create the solution to identify, aggregate and visualize KungFu bonds.

## Pre-requisites:
The code can be run on Refinitiv Codebook or Jupyter Notebook that has Refinitiv Data Platform (RDP) library installed and ready to be used. To run examples in this article, I'll be using the Codebook.
  -	In case you’re running the Jupyter Notebook in your own environment (not using Codebook),
    - The Access Credential is required to use RDP libraries. For more detail, please check this page RDP libraries - Access Credentials.
    - Required python libraries:
  -	Using Codebook, the key ‘DEFAULT_CODE_BOOK_APP_KEY’ can be used 
You may contact your Refinitiv's representative to help you to access Refinitiv workspace/Eikon.

### Required python libraries and their version:
you may download requirements.txt from this repo then use the command `pip install -r requirements.txt` to install required libraries
-	refinitiv.dataplatform==1.0.0a10
-	pandas==1.3.5
-	plotly==5.3.1
-	datetime==4.3
-	dateutil==2.8.2

## Example output
1) TRBC Pie

![kungfu-bond-vis-1-trbc-pie](https://user-images.githubusercontent.com/89068039/154163241-64580021-f4a3-4b70-80a0-dbadd4006b33.png)

2) Bond Grade Pie

![kungfu-bond-vis-2-bond-grade-pie](https://user-images.githubusercontent.com/89068039/154163259-3b483767-c1ef-4620-ac04-693e1f8f0622.png)

3) Issued amount last 12 months

![kungfu-bond-vis-3-bond-issued-amt-12-m](https://user-images.githubusercontent.com/89068039/154163269-784d79f3-6640-4ff3-a7ca-e622f02f0a89.png)

4) Redem amount in 10 years

![kungfu-bond-vis-4-bond-redem-amt-10-y](https://user-images.githubusercontent.com/89068039/154163278-5015d53c-015e-4467-9fe8-035199ddacf2.png)

5) Newly issued bonds last 3 months

![kungfu-bond-vis-5-bond-newly-issued-3m](https://user-images.githubusercontent.com/89068039/154163285-3f2320d8-fc8a-4cf5-a88f-d43e701a3e2c.png)

6) Price top 10

![kungfu-bond-vis-6-bond-price-top-10](https://user-images.githubusercontent.com/89068039/154163292-31f93e44-ad48-4b92-a0e9-c190c9a3fa0f.png)

7) Yield top 10

![kungfu-bond-vis-7-bond-yield-top-10](https://user-images.githubusercontent.com/89068039/154163300-8ee0e276-0fd5-4e4e-a851-6f35332bf002.png)

8) Yield last 10

![kungfu-bond-vis-8-bond-yield-last-10](https://user-images.githubusercontent.com/89068039/154163311-81339e1b-8ac9-46b4-aed0-8d527275687c.png)
