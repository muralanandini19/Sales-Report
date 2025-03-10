                    SALES REPORT



Dashboard Link :https://app.powerbi.com/groups/me/reports/489bb884-1156-4745-95de-4236a602a8cf/d602dbd4705f7419773f?experience=power-bi


Procedure:

1.	Importing the Dataset:
	Launch Power BI Desktop.
	Click on "Get Data" in the Home tab of the ribbon.
	Select the appropriate data source option "Excel” and follow the prompts to import your sample dataset into Power BI.


2.	Insert Rectangle Shape:

	Click on “Format tab” on right side and perform changes on visual.
	Shape > Style > #E66C37
	Shape > Text >Text = “Sales report” , Font Size = 46, Horizontal Alignment = “Center”.


3.	Add Card with Current Date:
	With the card visualization selected, locate the "Fields" pane on the right-hand side.
	Right-click anywhere in the "Fields" pane and select "New Measure" from the context menu. This will open the formula bar at the top.
	In the formula bar, enter the following DAX formula to create a measure that calculates the current date:
CurrentDate = Now()
	Press Enter to apply the formula.
	Visualization >Format Visual > General > Effects > Background Color : #E6E6E6
	Visualization > Format Visual >Visual > Category Label > Font Size = 12

4.	Create Stacked Bar Chart:
	Visualizations >Build Visuals >Fields > Y –Axis =”Category”
	Visualizations >Build Visuals >Fields > X-Axis =”Sales”
	Visualizations >Format Visuals> Y-axis> Values >Color = #6B2328
	Visualizations >Format Visuals> Y-axis> Values >Title >Color = #E66C37
	Visualizations >Format Visuals> Y-axis> Values >Color = #6B2328
	Visualizations >Format Visuals> Y-axis> Values >Title >Color = #E66C37
	Visualizations >Format Visuals> Bar> Show All
	Visualizations >Format Visuals> Bar> Technology > Color = #A1343C
	Visualizations >Format Visuals> Bar> Furniture > Color = #6D5A00
	Visualizations >Format Visuals> Bar> Office Supplies> Color = #09124F
	Visualizations >Format Visuals> Data Labels > Options> Inside Center
	Visualizations >Format Visuals> Data Labels> Values > Font Size = 18
	Visualizations >Format Visuals> Title> Text =”Sale by Category”
	Visualizations >Format Visuals> Title> Font Size =25
	Visualizations >Format Visuals> Effects> Background Color = #E6E6E6
 


5.	Create a Card to display Sum of Sales:
	With the card visualization selected, locate the "Fields" pane on the right-hand side.
	Drag “Sales” to “Fields”.
	Visualization >Format Visual > General > Effects > Background Color : #E6E6E6
	Visualization > Format Visual >Visual > Category Label > Font Size = 24


6.	Create a Card to display Total Orders:
	With the card visualization selected, locate the "Fields" pane on the right-hand side.
	Drag “OrderID” to “Fields” and change it to count orders.
	Visualization >Format Visual > General > Effects > Background Color : #E6E6E6
	Visualization > Format Visual >Visual > Category Label > Font Size = 24


7.	Create a Card to display Total Orders:
	With the card visualization selected, locate the "Fields" pane on the right-hand side.
	Drag “Profit” to “Fields”.
	Visualization >Format Visual > General > Effects > Background Color : #E6E6E6
	Visualization > Format Visual >Visual > Category Label > Font Size = 24



8.	Create Donut Chart:
	Drag “Regions” to Legend , “Sum of Sales” to Values.
	Visualizations > Build Visual > Legend > option =”Bottom Center”
	Visualizations > Build Visual > Legend > Text>Font =12
	Visualizations > Build Visual > Detail Labels >Position =”Center”
	Visualization >Format Visual > General > Effects > Background Color : #E6E6E6
	Visualizations >Format Visuals> Data Labels> Values > Font Size = 14



9.	Create a Line Chart:
	Visualizations > Build Visual > X-axis =”Order Date” by Year, Quarter
	Visualizations > Build Visual > Y-axis =”Sum of Sales”
	Visualizations > Format Visual > Visual > X-axis > Color = #0D6ABF
 

	Visualizations > Format Visual > Visual > Y-axis > Color = #0D6ABF
	Visualizations > Format Visual > General > Title > Text > Font > 20
	Visualization >Format Visual > General > Effects > Background Color : #E6E6E6


10.	Final Visual Format:
	Visualizations > Page Information > Name =”Sales report”
	Visualizations > Canvas Background > color = #12239E
	Visualizations > WallPaper > Color = #A0D1FF

 
12. Final Output


![Image](https://github.com/user-attachments/assets/2fbff716-9db2-43b9-a54c-73a46ac83730)
