<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Parkinson's Telemonitoring using Machine Learning</title>
</head>
<body>
    <h1>Parkinson's Telemonitoring using Machine Learning</h1>
    <p>This project utilizes various machine learning algorithms to analyze the Parkinson's Telemonitoring dataset, aiming to predict Parkinson's Disease progression and estimate UPDRS (Unified Parkinson's Disease Rating Scale) scores.</p>

    <h2>Key Features</h2>
    <ul>
        <li>Implemented machine learning models including Linear Regression, Support Vector Regressor (Grid Search CV), Decision Tree (Grid Search CV), Gradient Boost, Ada Boost (Decision Tree), and TensorFlow Keras Dense (5 layers).</li>
        <li>Optimized feature space using Principal Component Analysis (PCA) to reduce multicollinearity and dimensionality.</li>
    </ul>

    <h2>Performance Metrics</h2>
    <p>The following table summarizes the performance of various algorithms used in this project for both training and testing phases:</p>
    
    <h3>Comparison Table for Used Algorithms</h3>
    <table border="1" cellspacing="0" cellpadding="5">
        <thead>
            <tr>
                <th>No.</th>
                <th>Algorithm</th>
                <th>MSE (Mean Squared Error)</th>
                <th>R² Score</th>
                <th>MAE (Mean Absolute Error)</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td rowspan="2">1</td>
                <td rowspan="2">Linear Regression</td>
                <td>Training: 55.73</td>
                <td>Training: 0.16</td>
                <td>Training: 6.31</td>
            </tr>
            <tr>
                <td>Testing: 56.01</td>
                <td>Testing: 0.12</td>
                <td>Testing: 6.31</td>
            </tr>
            <tr>
                <td rowspan="2">2</td>
                <td rowspan="2">Support Vector Regressor (Grid Search CV)</td>
                <td>Training: 0.80</td>
                <td>Training: 0.99</td>
                <td>Training: 0.22</td>
            </tr>
            <tr>
                <td>Testing: 13.29</td>
                <td>Testing: 0.79</td>
                <td>Testing: 0.22</td>
            </tr>
            <tr>
                <td rowspan="2">3</td>
                <td rowspan="2">Decision Tree (Grid Search CV)</td>
                <td>Training: 0.99</td>
                <td>Training: 0.99</td>
                <td>Training: 0.40</td>
            </tr>
            <tr>
                <td>Testing: 5.31</td>
                <td>Testing: 0.92</td>
                <td>Testing: 0.40</td>
            </tr>
            <tr>
                <td rowspan="2">4</td>
                <td rowspan="2">Gradient Boost</td>
                <td>Training: 0.37</td>
                <td>Training: 0.99</td>
                <td>Training: 0.42</td>
            </tr>
            <tr>
                <td>Testing: 1.85</td>
                <td>Testing: 0.97</td>
                <td>Testing: 0.42</td>
            </tr>
            <tr>
                <td rowspan="2">5</td>
                <td rowspan="2">Ada Boost (Decision Tree)</td>
                <td>Training: 0.16</td>
                <td>Training: 1.00</td>
                <td>Training: 0.24</td>
            </tr>
            <tr>
                <td>Testing: 0.75</td>
                <td>Testing: 0.99</td>
                <td>Testing: 0.24</td>
            </tr>
            <tr>
                <td rowspan="2">6</td>
                <td rowspan="2">TensorFlow Keras Dense (5 layers)</td>
                <td>Training: 0.49</td>
                <td>Training: 0.99</td>
                <td>Training: 0.39</td>
            </tr>
            <tr>
                <td>Testing: 1.36</td>
                <td>Testing: 0.98</td>
                <td>Testing: 0.39</td>
            </tr>
        </tbody>
    </table>

    <h2>Conclusion</h2>
    <p>The project demonstrates the efficacy of machine learning models, particularly ensemble methods and deep neural networks, in improving the accuracy of Parkinson's Disease detection and progression prediction. The results indicate that these models can serve as powerful tools in clinical settings for the telemonitoring of Parkinson's Disease.</p>

    <h2>References</h2>
    <p>Detailed performance metrics and methodology can be found in the related research papers.</p>
</body>
</html>
