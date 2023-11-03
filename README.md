# Numerical-Methods-Model-Training

<!DOCTYPE html>
<html>
<head>
    <style>
        table {
            border-collapse: collapse;
            width: 100%;
        }

        table, th, td {
            border: 1px solid black;
        }

        th, td {
            padding: 8px 12px;
            text-align: left;
        }

        th {
            background-color: #f2f2f2;
        }

        .alert {
            padding: 10px;
            background-color: #f9edcc;
            color: black;
            border: 1px solid #f0c36d;
        }
    </style>
</head>
<body>

<h2>Model Performance:</h2>

<table>
  <tr>
    <th>Model</th>
    <th>RMSE</th>
    <th>Comment</th>
  </tr>
  <tr>
    <td>Linear Regression</td>
    <td>3132.14</td>
    <td>Baseline model for comparison</td>
  </tr>
  <tr>
    <td>Random Forest</td>
    <td>2185.05</td>
    <td>Outperformed the baseline model</td>
  </tr>
  <tr>
    <td>XGBoost</td>
    <td>1990.95</td>
    <td>-</td>
  </tr>
  <tr>
    <td>LightGBM</td>
    <td>1635.81</td>
    <td>Best performing with the lowest RMSE</td>
  </tr>
</table>

<div class="alert">
  <b>Reviewer's comment:</b><br>
  It's great to see the progression from the baseline Linear Regression model to the more advanced models. LightGBM has shown to be the most effective in reducing the RMSE in this scenario. It might be useful to consider parameter tuning or feature engineering further to see if the performance can be enhanced even more.
</div>

</body>
</html>
