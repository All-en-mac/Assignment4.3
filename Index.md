<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Marksheet Table</title>
    <style>
        /* Basic styling to make the table readable and professional */
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
            font-family: Arial, sans-serif;
        }
        th, td {
            border: 1px solid #dddddd;
            text-align: center;
            padding: 10px;
        }
        th {
            background-color: #f2f2f2;
        }
        caption {
            font-size: 1.2em;
            font-weight: bold;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Academic Performance Portal</h1>
        <p>Semester 1 Grade Report and Marksheet</p>
    </header>

    <main>
        <!-- Student Marksheet Table -->
        <table>
            <caption>Student Semester 1 Marksheet</caption>
            
            <!-- Table Header -->
            <thead>
                <tr>
                    <th>Roll No</th>
                    <th>Student Name</th>
                    <th>Mathematics</th>
                    <th>Science</th>
                    <th>English</th>
                    <th>Total Marks</th>
                    <th>Average (%)</th>
                </tr>
            </thead>

            <!-- Table Body (5 Students, 3 Subjects) -->
            <tbody>
                <tr>
                    <td>101</td>
                    <td>Alex Johnson</td>
                    <td>85</td>
                    <td>90</td>
                    <td>78</td>
                    <td>253</td>
                    <td>84.3%</td>
                </tr>
                <tr>
                    <td>102</td>
                    <td>Jane Smith</td>
                    <td>92</td>
                    <td>88</td>
                    <td>95</td>
                    <td>275</td>
                    <td>91.7%</td>
                </tr>
                <tr>
                    <td>103</td>
                    <td>Robert Davis</td>
                    <td>76</td>
                    <td>65</td>
                    <td>80</td>
                    <td>221</td>
                    <td>73.7%</td>
                </tr>
                <tr>
                    <td>104</td>
                    <td>Emily Brown</td>
                    <td>88</td>
                    <td>92</td>
                    <td>90</td>
                    <td>270</td>
                    <td>90.0%</td>
                </tr>
                <tr>
                    <td>105</td>
                    <td>Michael Wilson</td>
                    <td>79</td>
                    <td>84</td>
                    <td>82</td>
                    <td>245</td>
                    <td>81.7%</td>
                </tr>
            </tbody>

            <!-- Table Footer (Class Average summary using Colspan) -->
            <tfoot>
                <tr>
                    <td colspan="2"><strong>Overall Class Average</strong></td>
                    <td><strong>84.0</strong></td>
                    <td><strong>83.8</strong></td>
                    <td><strong>85.0</strong></td>
                    <td colspan="2"><strong>252.8 (84.3%)</strong></td>
                </tr>
            </tfoot>
        </table>
    </main>

</body>
</html>