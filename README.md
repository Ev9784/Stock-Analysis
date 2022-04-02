# Stock Analysis   

## *Stock Analysis Project* 
Our client Steve wanted our team to analyze his dataset. The client wants to expand the dataset to include his entire stock market over the year(s) 2017 and 2018. Steve's major request is to execute his data outcomes in the shortest amount of time possible. As the client states, his original data set was not efficient enough.

### Project Overview ### 
The first thing we did for Steve was create a "ticket index" variable and it to equal zero before iterating over all the rows. We used the Tickerindex to access four different arrays. These output arrays: "tickerVolumes, tickerStartingPrices, and tickerEnding Prices. The Data being reviewed and compared for Steve is categorized into single data type(s)

 ![alt text](link)

### *Stock Analysis Tickers and Results* 
Once we were able to identify the growth opportunities (the outcomes per year for Steve's 2017 and 2018) and put them into single data types(s). Here is an example of the (12) tickers as a string

'Create a header row
   Cells(3, 1).Value = "Ticker"
   Cells(3, 2).Value = "Total Daily Volume"
   Cells(3, 3).Value = "Return"

   'Initialize array of all tickers
   Dim tickers(12) As String

   tickers(0) = "AY"
   tickers(1) = "CSIQ"
   tickers(2) = "DQ"
   tickers(3) = "ENPH"
   tickers(4) = "FSLR"
   tickers(5) = "HASI"
   tickers(6) = "JKS"
   tickers(7) = "RUN"
   tickers(8) = "SEDG"
   tickers(9) = "SPWR"
   tickers(10) = "TERP"
   tickers(11) = "VSLR"


Our team was able to create loops that we were able to review all the rows in the spreadsheet.

   '1b) Create three output arrays

   Dim tickerVolumes(12) As Long
   Dim tickerStartingPrice(12) As Single
   Dim tickerEndingPrice(12) As Single

   ''2a) Create a for loop to initialize the tickerVolumes to zero.
   For i = 0 To 11

     tickerVolumes(i) = 0
     tickerStartingPrice(i) = 0
     tickerEndingPrice(i) = 0


This step was set to = 0 to analyze all data in Steve's business spreadsheet.


### Stock Performance for 2017 & 2018
 Once we have increased the overall performance of the data set, we can compare the performance between the years. The least positive outcome was 2018, as the Data quickly showed us the most negligible stock outcomes. We were also able to locate outliers. These stocks performed "well" for both years or consistently bad stock(s) that year after in the red.

Example of outcome for 2018
 ![alt text](link)

Example of outcome for 2017
![alt text](link)

## Summary 

## Results

- **Stock Analysis Advantages***
   Significant advantages in the stock analysis are seeing stock growth and progression in positive and negative stocks. Examples are the slow growth in TERP. This may be a stock that Steve should put on his radar, as he can quickly recoup his initial investment and sell. This data set can also help individuals look at the year and year highs. Has something outperformed expectations? Should Steve decide to potentially sell a portion of his profits as the company has shown consistent growth? This is now something that Steve can quickly review at the finger type.

- **Stock Analysis Pros and Cons**
   Major setbacks with this type of project are syntax errors, especially for our team. Although we were as shown able to meet the client's needs, it took an extensive review of the text to run a successful script. This can potentially lead to future issues, as year after year, this can become less efficient for the client and our team.
