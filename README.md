Overview:

Final Analysis sheet consolidates all the output data from the three reference sheets, providing a comprehensive analysis across three distinct time frames: Daily, Monthly, and 5-Years Lookback. 
It includes various tables that systematically separate in-sample and out-of-sample return calculations, ensuring clear and 
structured data representation. For example, N/BN means N long and BN short, highlighting specific 
trading positions within the strategy.

Outputs: 

Key terms: 

In-Sample: Tested different index pairs using past data (2009–2014) and selected the 
best-performing pair for each month. 
Out-of-Sample: Applied those “best” pairs to future/unseen data (e.g., 2015–2024) to see if 
they still performed well. 


<img width="390" height="584" alt="image" src="https://github.com/user-attachments/assets/bb78c214-7b71-4ed0-af01-8fa92cf7a589" />

Insights: 

● BN/S appears most frequently as the top performer in both in-sample and out-of-sample 
periods, suggesting strong historical performance. 

● N/BN and NF/S also perform well across different months, indicating consistency.

● The best-performing pairs vary slightly between in-sample and out-of-sample periods, which 
suggests market dynamics shift over time, and strategies that worked well in-sample do not 
always translate perfectly to future data. 




5 Years Lookback: 

Monthly Return Aggregation (5-Year Lookback): 

● For each calendar month (e.g., January 2015), the cumulative return for that specific month was 
calculated over the previous five years (i.e., January 2010 to January 2014).

● This calculation was repeated for all 12 months and for each year in the dataset. 
Cross-Index Comparison: 

● The 5-year cumulative monthly return aggregation was performed across four major indices: 
Nifty 50, Sensex, Bank Nifty, and Nifty Midcap. 

● The index with the highest 5-year cumulative return for a given month was identified as the long 
candidate. 

● The index with the lowest return in the same month was identified as the short candidate. 
Long-Short Signal: 

● The resulting long-short position was denoted as a pair in the format: Long Index / Short Index 
(e.g., BN/S indicates a long position in Bank Nifty and a short position in Sensex).

● The returns calculated were based on Returns(BankNifty) - Returns(Sensex).  

Quarter1: 

<img width="738" height="545" alt="image" src="https://github.com/user-attachments/assets/9d3f6b5f-18c5-4ebc-b70d-633f4fe14b0e" />



BankNifty and Nifty Finance often appear in the long position whereas Sensex and Nifty are sometimes 
used as relative hedges.   

Bank Nifty often appears as the long index, suggesting that it historically tends to outperform other 
indices in the months of Jan–Mar. 

Sensex frequently appears as the short, hinting that it might underperform during the same time frames, 
potentially due to its limited sector representation compared to broader indices. 

Quarter2 

<img width="733" height="546" alt="image" src="https://github.com/user-attachments/assets/2fc647ac-d1e2-4e7b-8b45-cad41d78e5ea" />


BN/N (Bank Nifty vs Nifty) was a strong strategy in April and May, but since 2020, Sensex has started 
to perform better in May, showing a shift in trend. 

In June, Sensex has been the top performer in 9 out of 11 years, while Bank Nifty often ends up as the 
weaker index. 

April used to give steady gains, but recent years show more volatility and less consistent returns, 
highlighting the need to adjust strategies as market trends evolve. 
Quarter3 

<img width="714" height="540" alt="image" src="https://github.com/user-attachments/assets/560244f0-7789-489d-80d5-e69beaecd66b" />

July has mixed results. Recently (2021–2024), Nifty has outperformed Bank Nifty, while earlier years 
saw Sensex in long positions but with weak returns. 

August is the worst-performing month, with mostly negative or flat returns and no clear winning index. 
It’s highly unreliable for long-short strategies. 

September is more consistent. Since 2018, Nifty Finance (NF) has been the strongest performer, often 
beating Sensex and Bank Nifty, showing post-Q2 strength. 


Quarter 4 

<img width="757" height="548" alt="image" src="https://github.com/user-attachments/assets/4aa5f7ad-9307-4dff-9ee5-26540bd011a4" />

October is one of the most reliable months for long-short strategies, particularly favoring BN. 

BN/NF gained traction from 2020 onward (e.g., 2020, 2021, 2022, 2023, 2024) in October 

Bank Nifty has been the strongest index in October and November historically. However, since 2022, 
Sensex has started outperforming in November, indicating a trend shift.  

In December, Nifty has emerged as the top performer from 2020 onwards, showing growing strength 
during year-end. 

