## EDA Project - Sector performance during and immediately after a recession.
1. Overview<br />
2. Guidelines & File Name<br />
3. Presentation<br />

## 1. Overview
Our project tries to analyse the sector performance during and immediately after a recession. We studied the recovery of the recessions, the relationships between GDP and the recession, the Post COVID-19 Recession and the sector performence during the recession.

## 2. Guidelines & File Name
### Jupyter Note Guidelines:<br />
Inside the norebook, you only need to change the name and the date of the recession, all the plots will be created into the same folder via the noteook.<br />
  ``` python
  # Covid-19 from 2020,2,3 to 2020,4,1
  # Financial crisis (GFC) from 2007,12,3 to 2009,6,1
  # Dot-Com bubble from 2001,3,1 to 2001,11,1

  Period = "Dot-Com"
  this_year_start = datetime(2001,3,2)
  this_year_end = datetime(2001,11,3)

  sector_list = ['^SP500-40','^SP500-25','^SP500-30',"^SP500-35","^SP500-20","^SP500-45","^SP500-15","^SP500-60","^SP500-50","^SP500-55","^GSPE"]
  sector_name = ["Financials","Consumer Discretionary","Consumer Staples","Health","Industrials","Information Tech","Materials","Real Estate","Tele Services","Utilities","Energy"]

  thisyear = ['^SP500-40','^SP500-25','^SP500-30',"^SP500-35","^SP500-20","^SP500-45","^SP500-15","^SP500-60","^SP500-50","^SP500-55","^GSPE"]

  for stock in sector_list: 
      thisyear[sector_list.index(stock)] = yf.download(stock, this_year_start, this_year_end)
  ```
### [Ash's Part](https://github.com/MAICATRAN/Group_Project1/tree/main/Ash's%20Part)
- Folders contain all the plot results.<br />
   - Covid-19<br />
      All the polts during this crash.<br />
   - The Golbal Financial crisis(GFC)<br />
      All the polts during this crash.<br />
   - Dot-Com Bubble<br />
      All the polts during this crash.<br />
   - S&P 500<br />
     - Plot for Return of the S&P 500 over 4 crashes <br />
     - Plot for Current Sector Distribution on S&P 500.<br />
   - sp500<br />
     - CSV file for the details of current 500 listed companies.<br />

### [Chris_Branch](https://github.com/MAICATRAN/Group_Project1/tree/main/Chris_Branch)
- Contains the following folders:<br />
   - COVID_Recession<br />
      Contains CSV files of market data for all sectors during COVID recession.<br />
   - Dot_Com_Recession<br />
      Contains CSV files of market data for all sectors during Dot-Com recession.<br />
   - GFC_Recession<br />
      Contains CSV files of market data for all sectors during GFC recession.<br />
   - Post_COVID_Recession<br />
      Contains CSV files of market data for all sectors from end of COVID recession to now.<br />
   - Post_Dot_Com_Recession<br />
      Contains CSV files of market data for all sectors from end of Dot-Com recession to now.<br />
   - Post_GFC_Recession<br />
      Contains CSV files of market data for all sectors from end of GFC recession to now.<br />
   - Project_1_Presentation<br />
      Contains the finished Word document (Project 1 - EDA Final), Powerpoint presentation (Project 1 - EDA Final) and drafts for this project.<br />
   - QRecs<br />
      Contains a file I shared with a teammate and can be ignored.<br />
   - SP500<br />
      Contains a CSV file listing all companies in the S&P500 complete with some summary information on each.<br />
      
      
- Contains the following documents:.<br />
   - Chris_Branch jupyter notebook.<br />
     - Please run it to generate the supporting tables and graphs that formed the foundation of my section of the report. <br />
     - Plot for Current Sector Distribution on S&P 500.<br />
   - Last_6_Recessions.docx<br />
     - A document with the recession start and end dates in it.<br />
   - PNG printouts of the many graphs that my code generates.<br />

- Usually I would take screen captures of the key features of my work, but everything I did is carefully described in the group's Word document.<br />

## 3. Presentation
- PowerPoint for The Project Introduction<br />
- Word Document for The Project comclusion<br />
