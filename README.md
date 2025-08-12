Quadratic Weather Modeling
This project demonstrates how to model temperature variations using a quadratic equation and visualize the results with Matplotlib.
It includes multiple implementations — fixed coefficients, user input, and CSV-driven plotting.
📌 Features
Quadratic temperature model: Uses a*t² + b*t + c formula.
Multiple input methods: Fixed values, user inputs, and CSV file.
Data visualization: Plots temperature vs. time/day using matplotlib.
CSV automation: Option to auto-create a CSV file for testing.
Multiple datasets: Compare different curves on the same graph.
🛠 Requirements
Install dependencies before running:
pip install matplotlib pandas
📂 Files
main_fixed.py → Example with fixed coefficients and days.
main_input.py → User enters a, b, c, and days.
main_csv.py → Reads coefficients from wea.csv or wea2.csv.
auto_csv.py → Creates CSV automatically and runs plotting.
wea.csv / wea2.csv → Coefficients for multiple models.
🚀 How to Run
1. Fixed Coefficients
python main_fixed.py
Enter the number of days when prompted.
2. User Input
python main_input.py
Follow prompts to enter coefficients and days.
3. Using CSV File
Ensure wea.csv exists:
a,b,c
-0.5,10,15
-0.3,8,12
-0.7,12,18
Then run:
python main_csv.py
4. Automatic CSV Creation (Recommended for Google Colab)
python auto_csv.py
This will:
Create wea.csv automatically.
Plot temperature curves for all datasets.
📊 Example Graph
The output will be a line chart showing how temperature changes over time for each set of coefficients.
📖 Formula Reference
Quadratic equation:
T(t)=a⋅t^2+b⋅t+c
a → curvature
b → slope
c → vertical shift
