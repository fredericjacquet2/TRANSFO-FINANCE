## Chapitre 4 - Technologies & solutions

1. ERP et produits spécifiques aux process
2. RPA Robotic Process Automation 
3. BI, cube OLAP, Dataviz et EPM
4. Big Data & analytics / IA  

----

### 4.1. ERP et produits spécifiques aux process    
<img src="images/erp3.png" style="background:none; border:none; box-shadow:none;"/>     

----

Produits pour gérer la digitalisation des process transacitonnels = modules ERP et/ou Apps spécifiques: 
- T&E : : [Jenji](https://jenji.io/en), [KDS](https://www.kds.fr/), [Traveldoo](https://www.traveldoo.com/) ...
- S2P / P2P : : [ESKER](https://www.esker.co.uk/), [BASWARE](https://www.basware.com/en-gb), [Tradeshift](https://tradeshift.com/), [Ivalua](https://fr.ivalua.com/) ...
- O2C : [Sidetrade](https://www.sidetrade.com/fr/produits/financials)(recouvrement)
- R2R : : [Oracle Hyperion Financial Management](https://www.oracle.com/applications/performance-management/products/financial-close-reporting/hyperion-financial-management/), [Blackline](https://www.blackline.com/) ...
- Cash management : [Kyriba](https://www.kyriba.fr/)
- Complicance : 

*Ces produits incluent et/ou peuvent être associés à des produits type RPA / Dataviz / IA*

----

### 4.2. RPA Robotic Process Automation

A robot automates human tasks, it works ideally if : 
- very repetitive tasks
- no intelligence

Number of available softwares availlable to do so, relative ease of configuration.     
ROI very dependent of repetitivity.

----

- A 3 minutes, neat & finance related video on an example of RPA implementation = [RPA 3min](https://youtu.be/xW95yb6J1eU)
- Another one in 7 minutes = [RPA 7min](https://youtu.be/loOR-nz9DGY)
- By the way, do you see social issue or social promise in those ?
- OK for reading ? A great tutorial, 20 minutes read : [RPA doc](https://www.guru99.com/robotic-process-automation-tutorial.html)
- Want more ? [RPA for dummies download](https://www.nice.com/websites/rpa/assets/robotic_process_automation_for_dummies.pdf)

----

> Case ARCELOR MITTAL (source Digital Finance Awards 2019)   

- Robotisation of Financial Processes within consolidation & reporting departments : 30 robots for 44 processes
- Excellent results in regards to productivity, performance, deliveralbes quality, time gain
- Led to a real innovation culture & change in mentalities witihn the teams

----

### 4.3. BI, cube OLAP, Dataviz et EPM

- Business intelligence (BI)  = applications, infrastructure and best practices that enable access to and analysis of information to improve and optimize decisions and performance.      
- BI process = collecting, organizing, and analyzing data, and turning it into useful and actionable information.     
- BI end-user functionalities : drill-down / roll-up, ad-hoc reports, interactive dashboards, mobile reports ...     

----

Data management (from raw data to fancy reporting)      
    
<img src="images/OLAP7.png" style="background:none; border:none; box-shadow:none;"/>      

----


<img src="images/OLAP3.jpg" style="background:none; border:none; box-shadow:none;"/>      

----

-	First challenge : centralising the data in a single Warehose (ETL products)     
-	Second challenge : have a quick & efficient access to required information (the OLAP cube)     
-	Third challenge : presenting the information in a clear, nice and tailored manner to the user (data visualisation functionalities)     
-	And a last challenge (for next chapter) : finding patterns in the warehouse’s data, in order to predict trends.  

----

The OLAP cube (Online Analytical Processing) : 

-	Pre-compute all the totals and subtotals needed for reporting
-	Totals are stored in a special database called « OLAP cube » which is a snapshot of data at a specific point of time.
-	OLAP cube efficiency : instant access to data (no need to loop through any transaction, as all totals are precalculated)
[5 min on OLAP & Relarional DB](https://www.youtube.com/watch?v=2ryG3Jy6eIY)

----

<img src="images/olap3.png" style="background:none; border:none; box-shadow:none;"/>      

More details on Bi implementation [here](https://www.altexsoft.com/blog/business/complete-guide-to-business-intelligence-and-analytics-strategy-steps-processes-and-tools/)

----

BI products : [Tableau](https://www.tableau.com/fr-fr), [Power BI](https://powerbi.microsoft.com/fr-fr/), [IBM Cognos]([Looker](https://looker.com/), [Chartio](https://chartio.com/), [Domo](https://www.domo.com/), [Qlik](https://www.qlik.com/us/), [IcCube](https://www.iccube.com/) ...
OLAP tools : IBM Cognos, MS SQLServer Analysis Services SSAS, 
FP&A / EPM (Enterprise Performance Management) products: Anaplan, 

----

### 4.4. Big Data & analytics / IA 

----

<img src="images/BIGData.png" style="background:none; border:none; box-shadow:none;"/>      

----

WIP Work In Progress 

----

*fin du chapitre 4 (Technologies & solutions)*
