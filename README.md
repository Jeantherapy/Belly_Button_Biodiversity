# Belly_Button_Biodiversity
**Belly Button Biodiversity Dashboard**

**Introduction**
The Belly Button Biodiversity Dashboard is an interactive web application that allows users to explore and analyze data related to the microbial biodiversity found in human belly buttons. This project aims to provide a visually appealing and user-friendly interface to delve into the fascinating world of microbial communities residing in our navels.

**Data Source**
The data used in the Belly Button Biodiversity Dashboard is sourced from a dataset called "samples.json." This dataset contains information about various test subjects and their corresponding microbial samples collected from their belly buttons. It includes demographic information, sample metadata, and microbial species data.

**Dashboard Features**
The Belly Button Biodiversity Dashboard offers several features for data exploration and visualization:

1. Test Subject Selection: The dashboard provides a dropdown menu to select a specific test subject ID. Choosing a subject triggers the update of all charts and metadata information based on the selected ID.

2. Demographic Information: The dashboard displays demographic information for the selected test subject, including age, gender, ethnicity, and location.

3. Horizontal Bar Chart: The bar chart showcases the top 10 microbial species found in the selected test subject's belly button. The chart represents the sample values (abundance) of each species, with the species labels displayed on the y-axis and the sample values on the x-axis.

  ![image 1](https://github.com/Jeantherapy/Belly_Button_Biodiversity/blob/main/Images/Horizontal%20Chart.png)

4. Bubble Chart: The bubble chart visualizes the distribution of microbial species across the selected test subject's belly button sample. Each bubble represents a specific microbial species, and its size corresponds to its abundance. The x-axis represents the OTU (Operational Taxonomic Unit) ID, and the y-axis represents the sample values.
  ![image 2](https://github.com/Jeantherapy/Belly_Button_Biodiversity/blob/main/Images/Gauge%20Chart.png)

5. Gauge Chart: The gauge chart displays the belly button washing frequency of the selected test subject. It represents the number of times the individual cleans their belly button per week using a gauge-like visualization.
  ![image 3](https://github.com/Jeantherapy/Belly_Button_Biodiversity/blob/main/Images/Bubble%20Chart.png)

**Customization and Extension**
The Belly Button Biodiversity Dashboard can be customized and extended in several ways:

1. Styling: The dashboard's appearance can be modified by changing the CSS styles, including fonts, colors, backgrounds, and layout.

2. Additional Charts: Users can enhance the dashboard by adding more visualizations, such as pie charts, line charts, or heatmaps, to provide further insights into the microbial data.

3. Interactive Elements: The dashboard can be expanded to include additional interactive elements, such as filters or sliders, to allow users to explore the data from different perspectives or focus on specific subsets of the dataset.

**Usage**
To use the Belly Button Biodiversity Dashboard, follow these steps:

1. Open the "index.html" file in a web browser.
2. Use the dropdown menu to select a test subject ID.
3. Explore the demographic information, bar chart, bubble chart, and gauge chart for the selected test subject.
4. Customize the dashboard, charts, or styling as desired by modifying the "charts.js" and "index.html" files.

**Conclusion**
The Belly Button Biodiversity Dashboard provides a captivating and informative interface for exploring and understanding the microbial biodiversity present in human belly buttons. With its intuitive charts and interactive features, users can gain insights into the complex microbial communities that inhabit our navels. By customizing and extending the dashboard, it can be adapted to accommodate further research, education, or data analysis requirements related to belly button biodiversity.
