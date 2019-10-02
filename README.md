# Data Visualization with Data Refinery

## 3. Use Data Refinery to visualize and clean data

Before we build our model we're going to take a quick detour to the *Data Refinery* tool. Data Refinery can quickly filter and mutate data, create quick visualizations, and do other data cleansing tasks from an easy to use user interface.

### Load the *BILLING* data table into data refinery

From the *Project* home, click on *Data sets*, *TABLE*, and choose the *USER123.BILLING* table.

![Launch the BILLING table](../.gitbook/assets/images/dr/dr-1-launch-billing.png)

Data Refinery should launch and open the data like the image below:

![Data Refinery view of the BILLING table](../.gitbook/assets/images/dr/dr-2-view-billing.png)

The *Operation* button can perform many tasks related to data cleansing such as: substituting values, removing and renaming columns, converting column types, etc.

![Data Refinery operations](../.gitbook/assets/images/dr/dr-3-operations.png)

Clicking on the *Profile* tab will bring up a quick view of several histograms about the data.

![Data Refinery Profile tab](../.gitbook/assets/images/dr/dr-4-profile.png)

Clicking on the *Visualizations* tab will bring up an option to choose which columns to visualize. In this case, we'll pick *TotalCharges*. Click on *Visualize data* when ready.

![Use Data Refinery to visualize data](../.gitbook/assets/images/dr/dr-5-visualize.png)

We can quickly see the data in a histogram by default, switching between different chart types in seconds.

![See the visualization in seconds](../.gitbook/assets/images/dr/dr-6-chart.png)
