# Box-Mueller-transformation
The Box-Mueller transformation can be used to obtain two independent and identically distributed (IID) Gaussian random variables (RVs) from two IID uniform RVs. generate M samples of the RVs R and Z and plot the probability density function (PDF) of each RV using histograms.
![Screenshot 2022-05-24 101717](https://user-images.githubusercontent.com/74524978/170094557-767e48ea-a697-46bb-abae-564cbecaf6cd.png)

The values used for M are 103 and 105. The code given generates M samples of uniformly distributed RVs R and Z between 0 and 1. 

The resulting plots which display the approximated and actual PDFs of R and Z for M = 103 are given below.
![1a_m3](https://user-images.githubusercontent.com/74524978/170095152-96ff34aa-b822-4cb3-9e49-97e4a352fa06.png)

The resulting plots which display the approximated and actual PDFs of R and Z for M = 105 are given below.
![1a_m5](https://user-images.githubusercontent.com/74524978/170095173-8b5a8d20-d4fa-4eb8-8520-492b8a95d164.png)

We can use the transformation to obtain samples of X and Y from the samples of R and Z. After execution of the code, the plot displaying the approximated and actual PDFs of X and Y for M = 103 are obtained.
![1b_m3](https://user-images.githubusercontent.com/74524978/170095581-c808855a-cc69-4462-81a4-469b57805420.png)

When executed for M = 105, the following plots are obtained.
![1b_m5](https://user-images.githubusercontent.com/74524978/170095602-eec680a9-955a-446d-a9c7-c0d8a8831b2e.png)
