# Ex03 Time Table
# Date:24/09/2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Slot Time Table</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 30px;
      background-color: white;
    }

    h2 {
      text-align: center;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      background-color:(215, 236, 20)lightcoral
    }

    th, td {
      border: 1px solid #452992;
      padding: 12px;
      text-align: center;
    }

    th {
      background-color: #007BFF;
      color: rgb(201, 17, 109);
    }

    td {
      height: 60px;
    }

    tr:nth-child(even) td {
      background-color: #aa8b98;
    }
  </style>
</head>
<body>

<h2>Weekly Slot Time Table - NIVETHA.S.K</h2>

<table>
  <tr>
    <th>Time Slot</th>
    <th>Monday</th>
    <th>Tuesday</th>
    <th>Wednesday</th>
    <th>Thursday</th>
    <th>Friday</th>
    <th>Saturday</th>
  </tr>
  <tr>
    <td>8:00 - 9:00</td>
    <td>Web</td>
    <td>cryp</td>
    <td>Web</td>
    <td>-</td>
    <td>C</td>
    <td>Cryp</td>
  </tr>
  <tr>
    <td>09:00 - 10:00</td>
    <td>Web</td>
    <td>Cryp</td>
    <td>Web</td>
    <td>-</td>
    <td>C</td>
     <td>Cryp</td>
  </tr>
  <tr>
    <td>10:00 - 11:00</td>
    <td>-</td>
    <td>Cryp</td>
    <td>Web</td>
    <td>C</td>
    <td>Web</td>
    <td>Web</td>
  </tr>
  <tr>
    <td>11:00 - 12:00</td>
    <td>-</td>
    <td>cryp</td>
    <td>web</td>
    <td>C</td>
    <td>web</td>
    <td>web</td>
  </tr>

  <tr>
    <td>12:00 - 1:00</td>
    <td colspan="6">Lunch Break</td>
  </tr>
  <tr>
    <td>1:00 - 2:00</td>
    <td>C</td>
    <td>-</td>
    <td>-</td>
    <td>cryp</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>2:00 - 3:00</td>
    <td>C</td>
    <td>-</td>
    <td>-</td>
    <td>Cryp</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>3:00 - 4:00</td>
    <td>-</td>
    <td>-</td>
    <td>C</td>
    <td>C</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>4:00 - 5:00</td>
    <td>-</td>
    <td>-</td>
    <td>C</td>
    <td>C</td>
    <td>-</td>
    <td>-</td>
  </tr>

</table>

</body>
</html>

<table>
  <tbody>
<h1>Course Details</h1>
    <tr>
      <th>S.No</th>
      <th>Code</th>
      <th>Course</th>
    </tr>
    <tr>
      <td>1</td>
      <td>CS3301</td>
      <td>Python programming</td>
    </tr>
    <tr>
      <td>2</td>
      <td>19AI414</td>
      <td>Fundamental of web application development</td>
      </tr>
    <tr>
      <td>3</td>
      <td>19CS547</td>
      <td>Fundamental of crypto currency</td>
    </tr>
  
  

    </tbody>
  </table>
<script>

```
# OUTPUT
<img width="1343" height="603" alt="Screenshot 2025-09-24 084515" src="https://github.com/user-attachments/assets/bad4b4f7-07a7-4c4c-8771-430f92400c87" />
<img width="1331" height="606" alt="Screenshot 2025-09-24 084535" src="https://github.com/user-attachments/assets/c07a51b4-3a87-4ab8-ba7b-4ff2277d6d06" />


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
