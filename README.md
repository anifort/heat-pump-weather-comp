# Weather Compensation Regression Chart

This is a dynamic, interactive web application designed to help you visualize and understand a weather compensation heating curve. By plotting your own data points, you can generate a linear regression line that predicts the optimal water temperature for your heating system based on outside temperature.

---

## Key Features

* **Interactive Chart**: Visualize your data points and the calculated linear regression line in real-time. 📈
* **Draggable Points**: Simply drag the blue data points on the chart to adjust their values. The regression line and slope will update instantly.
* **Custom Point Input**: Add new data points by entering the outside and internal temperatures. The app will calculate the required water temperature based on the regression line.
* **Regression Line & Slope**: The chart automatically calculates and displays the slope of the linear regression line, helping you understand the relationship between outside temperature and the target water temperature.
* **"Compare" Function**: Click the "Compare" button to save the current regression line as a faded dashed line, allowing you to easily compare a new line to an older one.
* **8°C Target Point**: A green dot is automatically placed on the chart at the standard 8°C outside temperature, showing you the calculated target water temperature at that specific point.
* **Data Table**: All data points you add are automatically listed in a table below the chart for easy reference. You can delete custom points from this table.

---

## How to Use

1.  **Set Main Values**: Use the "Cold weather" and "Hot weather" input fields to define your two primary data points. Click "Set Values" to apply them to the chart.
2.  **Adjust Points**: You can either enter values in the input fields or click and drag the blue dots on the chart directly. The inputs will update to reflect the chart's position.
3.  **Move with Arrow Keys**: Select a blue dot on the chart with a click, then use the arrow keys on your keyboard to make fine adjustments to its position.
4.  **Add New Points**: To add a custom point, enter the desired Outside Temperature and Internal Temperature in the "Add a New Point" section and click "Add Point."
5.  **Compare Lines**: Once you have a line you like, click the "Compare" button to save it as a faded reference line. Then, you can adjust your main points to see how a new curve compares.

---

## Technology Stack

* **HTML**: For the page structure and user interface.
* **Tailwind CSS**: For all styling and responsive design.
* **Chart.js**: A flexible JavaScript charting library used to create the interactive scatter and line charts.
* **Vanilla JavaScript**: For all the application logic, including calculations, event handling, and DOM manipulation.
