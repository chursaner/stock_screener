# Financial analysis in R using purrr and tidyquant

This is the first iteration of using R to create a custom stock screener. Currently, the script pulls a list of all possible ratios from tidyquant (pasted here as well) and narrows down to a few indicators per each stock in my list. You can use it to audit your current holdings, or evalutate your watch list, screen the entire NASDAQ, etc. 

# Ratios by Section
 $`Financial`
  [1] "Book Value Per Share * USD"     "Cap Spending USD Mil"          
  [3] "Dividends USD"                  "Earnings Per Share USD"        
  [5] "Free Cash Flow Per Share * USD" "Free Cash Flow USD Mil"        
  [7] "Gross Margin %"                 "Net Income USD Mil"            
  [9] "Operating Cash Flow USD Mil"    "Operating Income USD Mil"      
 [11] "Operating Margin %"             "Payout Ratio % *"              
 [13] "Revenue USD Mil"                "Shares Mil"                    
 [15] "Working Capital USD Mil"       
 
 $`Profitability`
  [1] "Asset Turnover (Average)"     "COGS"                        
  [3] "EBT Margin"                   "Financial Leverage (Average)"
  [5] "Gross Margin"                 "Interest Coverage"           
  [7] "Net Int Inc & Other"          "Net Margin %"                
  [9] "Operating Margin"             "Other"                       
 [11] "R&D"                          "Return on Assets %"          
 [13] "Return on Equity %"           "Return on Invested Capital %"
 [15] "Revenue"                      "SG&A"                        
 [17] "Tax Rate %"                  
 
 $`Growth`
 [1] "10-Year Average" "3-Year Average"  "5-Year Average"  "Year over Year" 
 
 $`Cash Flow`
 [1] "Cap Ex as a % of Sales"           "Free Cash Flow Growth % YOY"     
 [3] "Free Cash Flow/Net Income"        "Free Cash Flow/Sales %"          
 [5] "Operating Cash Flow Growth % YOY"
 
 $`Financial Health`
  [1] "Accounts Payable"              "Accounts Receivable"          
  [3] "Accrued Liabilities"           "Cash & Short-Term Investments"
  [5] "Current Ratio"                 "Debt/Equity"                  
  [7] "Financial Leverage"            "Intangibles"                  
  [9] "Inventory"                     "Long-Term Debt"               
 [11] "Net PP&E"                      "Other Current Assets"         
 [13] "Other Long-Term Assets"        "Other Long-Term Liabilities"  
 [15] "Other Short-Term Liabilities"  "Quick Ratio"                  
 [17] "Short-Term Debt"               "Taxes Payable"                
 [19] "Total Assets"                  "Total Current Assets"         
 [21] "Total Current Liabilities"     "Total Liabilities"            
 [23] "Total Liabilities & Equity"    "Total Stockholders' Equity"   
 
 $`Efficiency Ratios`
 [1] "Asset Turnover"         "Cash Conversion Cycle" 
 [3] "Days Inventory"         "Days Sales Outstanding"
 [5] "Fixed Assets Turnover"  "Inventory Turnover"    
 [7] "Payables Period"        "Receivables Turnover"  
 
 $`Valuation Ratios`
 [1] "Price to Book"      "Price to Cash Flow" "Price to Earnings" 
 [4] "Price to Sales"

