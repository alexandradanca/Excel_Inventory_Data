<h1 align="center">Inventory Datasets<br /></h1>
<h2>Scenario I</h2>
<p>I'm a recently hired Junior Data Analyst in a local government office, who has been tasked with importing some data from another department which relates to inventory information about their fleet of vehicles. The data is in comma-separated value (CSV) format and the data also needs cleaning up before you can start to run any kind of analysis on it.</p>
<h3>Clean and Prepare the Data</h3>
<p>The dataset used comes from the following source: <a href='https://data.montgomerycountymd.gov/Government/Fleet-Equipment-Inventory/93vc-wpdr/about_data'> link to dataset</a></p>
<ol>
  <li><b>Column widths:</b> Sort out the widths of all columns so that the data is clearly visible in all cells.</li>
  
  ![image](https://github.com/user-attachments/assets/fffd0d56-a800-492c-b153-df84cc960622)

  <li><b>Empty rows:</b> Use the Filter feature to look for blanks and remove all empty rows from the data.</li>

![image](https://github.com/user-attachments/assets/beb74ba5-80c5-418f-b5a5-0250bfac05df)

  <li><b>Duplicate records:</b> Use either the Conditional Formatting or Remove Duplicates feature to look for and remove any duplicated records from the data.</li>

![image](https://github.com/user-attachments/assets/39ecc342-89fd-4895-9774-f72bdfa83f1e)

  <li><b>Spelling:</b> The original source file data has not been checked for errors in the spelling. Check for spelling mistakes in the data and fix them.</li>
  <p>For Departament column:</p>
	<ul><li>Enviromnental -> Environmental </li></ul>
 <br/>
<p>For Department2 column:</p>
<ul>
  <li>Rehabilltation -> Rehabilitation</li>
	<li>Recsue -> Rescue</li>
	<li>Servcies -> Services</li>
 </ul>
 <br/>
<p>For Equipment Class column:</p>
	<ul><li>Off Road VehicleEquipment -> Off Road Vehicle Equipment </li></ul>

  <li><b>Whitespace:</b> Use the Find and Replace feature to remove all double-spaces from the data.</li>

  ![image](https://github.com/user-attachments/assets/1024e51d-19c4-4699-813e-6ef668300892)

  <li><b>Department names:</b> When the data was converted from its data source, the department names (see correct list below) didn’t import correctly and they are now split over two columns in the data. Use Flash Fill to reduce the department names to just one column, and then remove any unnecessary columns.</li>

  ![image](https://github.com/user-attachments/assets/7193c8dc-21a4-4033-8088-5b36328d8cd4)

</ol>


<h2>Scenario II</h2>
<p>I'm a recently hired Junior Data Analyst in a local government office, who has been tasked with sorting and analyzing fleet inventory data that was previously imported and cleaned. You plan to use pivot tables to analyze the data in preparation for the results to be visualized in a dashboard and added to a data findings report later.</p>
<h3>Analyze the Data</h3>
<p><b>Format the data as a table:</b> Use the Format as Table option to format the data as a table.</p>

![image](https://github.com/user-attachments/assets/ff2bb06f-c015-4d51-9f95-a5660d17af08)

<p><b>Create a Pivot Table:</b> Use the PivotTable feature to create a pivot table that displays the Department field in the Rows section, and the Equipment Count in the Values section, so that the pivot table displays the sum of equipment count by department.</p>

![image](https://github.com/user-attachments/assets/d8f0c81c-cb86-4e1f-9a65-932bd4f19b8f)

<p><b>Sort the pivot table data:</b> Use the Sort By Value setting on the pivot table to sort it in descending order by the sum of equipment count.</p>

![image](https://github.com/user-attachments/assets/f33e1eb6-0c84-4cef-9e17-f8f5b71914c4)

<p><b>Make two more pivot tables exactly the same as previoustask:</b> Follow the same steps you performed in previous tasks to create two more identical pivot tables so that you end up with 3 worksheets that contain identical pivot tables.</p>
<p>Analyze data in the pivot table: Use the PivotTable Fields pane to manipulate and analyze data in the two copied pivot table as follows:</p>
<ul>
	<li>In pivot table 2 add the Equipment Class field below the Department field so that the different vehicle types appear under each department with their respective counts.</li> 
	<li>Collapse all fields except the top one - Transportation</li> 
	<li>In pivot table 3 add the Equipment Class field above the Department field so that the different vehicle types appear first, with the different departments listed underneath each vehicle type with their respective counts.</li> 
	<li>Collapse all fields except the top one - CUV</li> 
</ul>

  ![image](https://github.com/user-attachments/assets/e3777d97-aaa9-420b-a9a9-16d1fdf890b1)

 ![image](https://github.com/user-attachments/assets/7693c204-062d-416b-bed5-642829237a87)
