## ⚽ Saudi League Champions Website

### 🌍 Project Overview  
This project is a simple static website that showcases the winning clubs of the Saudi Professional League (Roshn Saudi League) over the last 10 seasons. It is built using pure HTML and CSS and is designed to run locally using XAMPP.

---

### 🧱 Technologies Used  
- HTML5 – For page content and structure  
- CSS3 – For design, layout, and table styling  
- XAMPP – Local server environment (Apache) to run the site on localhost

---

### 🏆 Features  
- Clean and responsive layout  
- Arabic language support with RTL (right-to-left) design  
- Displays a styled table of league winners from the last 10 seasons  
- Easy to read and customize  

---

### 📄 File Structure  
copy


htdocs/
└── saudi-league/
    └── index.html   ← Main HTML file

---

### 🔧 How to Run  

1. Install XAMPP on your computer.  
2. Place the project folder saudi-league inside:  
   C:\xampp\htdocs  
3. Open XAMPP Control Panel and start Apache.  
4. In your browser, go to:  
   http://localhost/saudi-league/

---

### 📸 Screenshot  

Below is a screenshot of the website interface:

![Screenshot](https://github.com/JawaherMQ5/xampp/blob/main/Roshn%20Saudi%20league.jpg)



### 📊 Data Sample  

| Season     | Champion     |
|------------|--------------|
| 2024-2025  | Al-Ittihad   |
| 2023-2024  | Al-Hilal     |
| 2022-2023  | Al-Ittihad   |
| 2021-2022  | Al-Hilal     |
| 2020-2021  | Al-Hilal     |
| 2019-2020  | Al-Hilal     |
| 2018-2019  | Al-Nassr     |
| 2017-2018  | Al-Hilal     |
| 2016-2017  | Al-Hilal     |
| 2015-2016  | Al-Ahli      |

### CODE

<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <title>الدوري السعودي - آخر 10 مواسم</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            direction: rtl;
            text-align: center;
            background-color: #f9f9f9;
            padding: 40px;
        }

        h1 {
            color: #006c35;
        }

        table {
            margin: 0 auto;
            border-collapse: collapse;
            width: 80%;
            background-color: #ffffff;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        th, td {
            padding: 12px 16px;
            border: 1px solid #ccc;
        }

        th {
            background-color: #006c35;
            color: white;
        }

        tr:nth-child(even) {
            background-color: #f1f1f1;
        }
    </style>
</head>
<body>

    <h1>أبطال الدوري السعودي - آخر 10 سنوات</h1>

    <table>
        <tr>
            <th>الموسم</th>
            <th>النادي الفائز</th>
        </tr>
        <tr><td>2024-2025</td><td>الاتحاد</td></tr>
        <tr><td>2023-2024</td><td>الهلال</td></tr>
        <tr><td>2022-2023</td><td>الاتحاد</td></tr>
        <tr><td>2021-2022</td><td>الهلال</td></tr>
        <tr><td>2020-2021</td><td>الهلال</td></tr>
        <tr><td>2019-2020</td><td>الهلال</td></tr>
        <tr><td>2018-2019</td><td>النصر</td></tr>
        <tr><td>2017-2018</td><td>الهلال</td></tr>
        <tr><td>2016-2017</td><td>الهلال</td></tr>
        <tr><td>2015-2016</td><td>الأهلي</td></tr>
    </table>

</body>
</html>

