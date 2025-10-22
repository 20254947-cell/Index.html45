<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weekly Diet & Exercise Tracker</title>
</head>
<body>
    <table border="1" width="90%" align="center">
        <tr>
    <td colspan="2" align="center" bgcolor="grey"><br><br>
    <h1>Weekly Diet & Exercise Tracker</h1>
    <p>Monitor your meals and workouts for a healthier lifestyle.</p>
    </td>
    </tr>
    <tr>
        <td width="50%" valign="top">
            <form>
                <fieldset>
                    <legend>Personal Info</legend>
                    Name:<input type="text" name="Name"><br>
                    Age:<input type="number" name="Age"><br>
                    Gender:
                    <select name="Gender">
                    <option value="">--Select--</option>
                    <option value="Male">Male</option>
                    <option value="Female">Female</option>   
                    </select>
                    </fieldset>
                    <br>
                    <fieldset>
                    <legend>Diet Tracking (Mon-Fri)</legend>
                    <table border="1">
                    <tr>
                    <th>Day</th>
                    <th>Calories</th>
                    </tr>
                    <tr><td>Mon</td><td><input type="text" name="mon_meal"></td></tr>
                    <tr><td>Tue</td><td><input type="text" name="tue_meal"></td></tr>
                    <tr><td>Wed</td><td><input type="text" name="wed_meal"></td></tr>
                    <tr><td>Thu</td><td><input type="text" name="thu_meal"></td></tr>
                    <tr><td>Fri</td><td><input type="text" name="fri_meal"></td></tr>
                    </table>
                    </fieldset>
                    <br>
                    <fieldset>
                    <legend>Exercise (Mon-Fri)</legend>
                    <table border="1">
                    <tr>
                    <th>Day</th>
                    <th>Minutes</th>
                    </tr>
                    <tr><td>Mon</td><td><input type="text" name="mon_ex"></td></tr>
                    <tr><td>Tue</td><td><input type="text" name="tue_ex"></td></tr>
                    <tr><td>Wed</td><td><input type="text" name="wed_ex"></td></tr>
                    <tr><td>Thu</td><td><input type="text" name="thu_ex"></td></tr>
                    <tr><td>Fri</td><td><input type="text" name="fri_ex"></td></tr>
                    </table>
                    </fieldset>
                    <br>
                    <input type="submit" value="Submit">
                    <input type="reset" value="Reset">
                    </form>
                    <td>
                    <td width="50%" valign="top" align="center">
                    <h3>Motivational Fitness Video</h3>
                    <iframe src="https://www.youtube.com/embed/gF0rrpMH-Jo" allowfullscreen></iframe>
                </td>
            </tr>    
       </table>
</body>
</html>
