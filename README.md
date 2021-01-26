### General info
Repository contains datasets of NIFTY50 INDEX,RELIANCE,TCS,HDFCBANK and HINDUNILVR
	
### Technologies
Datasets imported from:
* Google Finance using Google spreadsheet
	
### Setup
If other companies' datasets needed:
### Use the GOOGLEFINANCE function in Google spreadsheet
1. In Sheets, open a spreadsheet.
2. In an empty cell, type =GOOGLEFINANCE.
3. In parenthesis, add any of the following, separated by a comma:
    * A ticker symbol in quotation marks.
    * (Optional) The attribute you want to show, such as price, in quotation marks.
    * (Optional) A start and an end date preceded by DATE and followed with the numerical date in parenthesis.
    * (Optional) Daily or weekly frequency in quotation marks.
4. Press Enter.

>For example:
>To list the INFOSYS stock price, from 2000 till date, you type:
>=GOOGLEFINANCE("NSE:INFOSYS", "all", DATE(2000,1,1),TODAY(), "DAILY")
### To Learn more about GOOGLEFINANCE function in Google spreadsheet 
>https://support.google.com/docs/answer/3093281


