# 28_june-ex-html
first class html simple coding for creating the table

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        table,th,td{
            border:2px solid red;
            border-collapse:collapse;
        }
    </style>
</head>
<body>
    <table>
        <thead>
            <tr>
                <th>State of health</th>
                <th colspan="2">Fasting Value</th>
                <th colspan="1">After Remaining</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td></td>
                <th>Minimum </th>
                <th>Normal</th>
                <th>2 hours of Eating</th>
            </tr>
            <tr>
                <td>healthy</td>
                <td>70</td>
                <td>100</td>
                <td>Less than 140</td>
            </tr>
            <tr>
                <td>Pre-Diabetes</td>
                <td>101</td>
                <td>126</td>
                <td>140 to 200</td>
            </tr>
            <tr>
                <td>Diabetes</td>
                <td>more than 126</td>
                <td>Not Applicable</td>
                <td>More than 200</td>
            </tr>
    </tbody>
    </table>
</body>
</html>
