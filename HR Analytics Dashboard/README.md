# HR Analytics Dashboard

Dashboard to show HR about the various features regarding the attrition of employees in the company. The dashboard can be filtered by departments to show attrition within each department or overall attrition. The dashboard is published on Tableau server and looks like as shown below.
<p align='center'>
  <img src="images/Dashboard.jpg" width=900 height=500/>
</p>
<br/>

## Components
**Attrition by Job Satisfaction:**&nbsp;
<img src="images/pie_chart.jpg" width=350 height=300 align="left"/>
  &nbsp;&nbsp;
  - The sum of Attrition dimension is added as the angle of the pie-chart.
  - Job Satisfaction dimension is filled in the pie-chart with arranging required colors from the marks pane.
  - Tooltip and title are adjusted accordingly.
<br clear="left"/>
<br/>

**Attrition by Performanct Rating:**&nbsp;
<img src="images/attrition by performance.jpg" width=500 height=300 align="left"/>
  &nbsp;&nbsp;
  - The sum of Attrition dimension is added in the rows field.
  - Performace Rating and monthly income dimensions are added in the columns field, with the former as a dimension instead of a measure.
  - The bar chart are filled with hue of the monthly income by putting it in colors field in the marks pane.
  - Tooltip and title are adjusted accordingly.
<br clear="left"/>
<br/>

**No. of Employees by Age:**&nbsp;
<img src="images/employees by age.jpg" width=500 height=300 align="left"/>
  &nbsp;&nbsp;
  - The sum of Attrition dimension is added in the rows field.
  - Created age bins by using the age column and used the parameter to create a slider to change bin size.
  - Tooltip and title are adjusted accordingly.
<br clear="left"/>
<br/>

**Attrition by % Salary Hike:**&nbsp;
<img src="images/perc sal hike.jpg" width=500 height=300 align="left"/>
  &nbsp;&nbsp;
  - The sum of Attrition dimension is added in the columns field.
  - Created percentage salary hike bins by using the percentage salary hike column and used the parameter to create a slider to change bin size.
  - Tooltip and title are adjusted accordingly.
<br clear="left"/>
<br/>

**Attrition by Age Group/Gender:**&nbsp;
<img src="images/attr by gender and age.jpg" width=800 height=200 align="left"/> <br clear="left"/>
  - Create age bands from the age dimension, and put it in columns field.
  - Filled the angle of the pie chart with attrition and put gender in the color marks pane.
  - Tooltip and title are adjusted accordingly.
