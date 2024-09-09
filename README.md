# Atliq-Financial-Analytics-Report

𝐎𝐛𝐣𝐞𝐜𝐭𝐢𝐯𝐞
AtliQ Hardware, a hardware retail company, offers a range of products such as PCs, mouse, printers, etc. Its customers like Croma, Amazon, Best Buy Flipkart, etc. Tasked by AtliQ's Business users, the objective is to harness data from files containing over 1.5 million records to prepare sales and financial reports.
 
S𝐭𝐞𝐩𝐬 𝐢𝐧𝐯𝐨𝐥𝐯𝐞𝐝 𝐢𝐧 𝐦𝐚𝐤𝐢𝐧𝐠 𝐭𝐡𝐢𝐬 𝐑𝐞𝐩𝐨𝐫𝐭
 
1. 𝐄𝐓𝐋 (𝐄𝐱𝐭𝐫𝐚𝐜𝐭 𝐓𝐫𝐚𝐧𝐬𝐟𝐨𝐫𝐦 𝐚𝐧𝐝 𝐋𝐨𝐚𝐝)
Load all the CSV files that were provided, to Power Query. Ensured there were no missing values, all dimension tables contained a unique column, removed duplicate values, corrected the spelling errors, and in the end loaded the files in the Power Pivot.
 
2. 𝐃𝐚𝐭𝐚 𝐌𝐨𝐝𝐞𝐥𝐢𝐧𝐠
Connect all the tables using star schema. Create a new table dim_date using Power Query that includes the date, month, and year in a separate column. Add a new column for adding AtiliQ Hardware Fiscal year that runs from September to August and then connect the table with others.
 
3. 𝗣𝗶𝘃𝗼𝘁 𝗧𝗮𝗯𝗹𝗲 𝗮𝗻𝗱 𝗣𝗼𝘄𝗲𝗿 𝗣𝗶𝘃𝗼𝘁
Integrate the data model with a Pivot Table for quick data analysis. Utilize Power Pivot to create new measures and columns. Employ Power Query for seamless data transformation and connectivity.
 
4. 𝐃𝐀𝐗 (𝐃𝐚𝐭𝐚 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬 𝐄𝐱𝐩𝐫𝐞𝐬𝐬𝐢𝐨𝐧)
Create 10 + new Measures such as Net sales for each year, Gross Margin, GM %, and COGS using Formulas like Calculate, Sum, Divide, etc. Create new Columns using Functions like Related, Calculate, Format and extract quarterly months by adding 4 months to the calendar year for a fiscal year perspective.
 
5.  𝐂𝐨𝐧𝐝𝐢𝐭𝐢𝐨𝐧𝐚𝐥 𝐅𝐨𝐫𝐦𝐚𝐭𝐭𝐢𝐧𝐠 
Applied Conditional Formatting to enhance data presentation by applying rules, and formatting numbers and text. This approach highlights important data, identifies trends, and improves overall data readability for more effective analysis.
 

𝐈𝐧𝐬𝐢𝐠𝐡𝐭𝐬
1. India emerges as the forerunner in net sales at a staggering 161.3M
2. AQ Master wired x1 Ms takes the crown as our highest-sold product
3. Festive seasons witness soaring sales from October to December.

