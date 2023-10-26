# Project Highlights:

a. Exploring and Preprocessing Data 
•	Understanding the data: The dataset provided contained critical information, with a focus on the 'Date' and 'Close' columns, presenting a typical time series data problem.
•	Data preprocessing: To effectively tackle the time series challenge, I divided the dataset into input and output segments, implementing a window size of 5 (covering Monday to Friday) and a horizon of 1 (Monday only).

b. Building a Baseline LSTM Architecture [5 points]:
•	LSTM model: I constructed a baseline architecture featuring an LSTM layer with 50 units, followed by a Perceptron node with 1 unit.
•	Activation function: ReLU was employed as the activation function for the LSTM layer.

c. Optimization and Model Refinement [15 points]:
•	Experimenting for optimal results: After evaluating the initial model's performance, I engaged in a comprehensive optimization process.
•	Hyperparameter tuning: I fine-tuned the architecture by adjusting hyperparameters and modifying the network's structure.
•	Rationale: My decisions were driven by empirical results and data-driven insights. I thoroughly explain the rationale behind each modification in the report, showcasing my data-driven approach.

d. Performance Evaluation
•	Model assessment: I assessed the performance of both the baseline and optimized architectures using industry-standard metrics like Root Mean Square Error (RMSE), Mean Absolute Error (MAE), and Mean Absolute Percentage Error (MAPE).
•	Detailed analysis: In my report, I provide a comprehensive analysis of the results, highlighting the strengths and limitations of each architecture.

