# 🏠Mortgage-Lending-Notebook [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1cVYFSh35U2sVySf9CBrQzQ1xPj-cXmz4?usp=sharing)
This is an interactive Jupyter notebook that uses API socket to extract latest & historic lending series from Bank of England. Holdings of Mortgage securities and Lending data are aggregated across all UK Resident Banks (Monetary Financial Institutions);
## Tutorial GIF
![](https://github.com/viczommers/Mortgage-Lending-Notebook/blob/main/Mortgage_Tutorial.gif)
## Scenario Analysis
The app plots mortgage series scatter plot and distribution curve from all historic data points for a selected target range of BOE Bank Rate.
## Data
Notebook covers:
- Gross Bank lending to individuals (secured on dwelling), NSA [(Series Code: LPQB3VB)](https://www.bankofengland.co.uk/boeapps/database/FromShowColumns.asp?Travel=&searchText=LPQB3VB)
- Amounts outstanding of structured mortgage securities (assets) held on Banks' balance sheets, NSA [(Series Code: LPMB7GT)](https://www.bankofengland.co.uk/boeapps/database/FromShowColumns.asp?Travel=&searchText=LPMB7GT)
- Value of total mortgage approvals issued to households, SA [(Series Code: LPQVTVQ)](https://www.bankofengland.co.uk/boeapps/database/FromShowColumns.asp?Travel=&searchText=LPQVTVQ)
- Write-offs of Bank mortgage lending (i.e. technical defaults & bad credit provisions), NSA [(Series Code: RPQTFHD)](https://www.bankofengland.co.uk/boeapps/database/FromShowColumns.asp?Travel=&searchText=RPQTFHD)
- Average Quarterly BOE Bank Rate, NSA [(Series Code: IUQABEDR)](https://www.bankofengland.co.uk/boeapps/database/FromShowColumns.asp?Travel=&searchText=IUQABEDR)
<br> All values are displayed in £ millions;
## Method
> Here we use Plotly graphic package with simple iPywidgets inputs to create dynamic visualisations. This is a simple solution for building interactive Jupyter notebooks (which is more robust than using Flask framework).
- This repo includes local machine version of Notebook (that uses default render).
- iPywidgets interactivity **will be enabled only when the code cell is executed in a kernell**.
