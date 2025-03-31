<!DOCTYPE html>
<html>
    <head>
        <title>This is my first PLP Webpage</title>
    </head>
    <body>
        <!-- This is the beginning of the ordered list -->
        <h3>Ordered List with Numerals</h3>
        <ol type="i">
            <li>Carrots</li>
            <li>Cabbages</li>
            <li>French Beans</li>
            <li>Tomatoes</li>
            <li>Onions</li>
        </ol>
        <br>
        <!-- This is the end of ordered list -->
        <img src="winter.jpeg" alt="Image of winter landscape" width="200" height="200">
        <br><br>
        <!-- image has alredy been inserted -->
        <table border="1">
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Emails</th>
                </tr>
            </thead>
            <tbody>
                <td>Linet</td>
                <td>Maraba</td>
                <td>0740776569</td>
                <td>nyithyalinet@gmail.com</td>
            </tbody>

            <tbody>
                <td>Robert</td>
                <td>Runda</td>
                <td>0743845678</td>
                <td>robertkioko@gmail.com</td>
            </tbody>

            <tbody>
                <td>Mutanu</td>
                <td>Mombasa</td>
                <td>0734787123</td>
                <td>mutanupurity@gmail.com</td>
            </tbody>
            <tbody>
                <td>Ronaldo</td>
                <td>Kahawa Wendani</td>
                <td>0712765349</td>
                <td>ronnthenya@gmail.com</td>
            </tbody>

            <tbody>
                <td>Japheth</td>
                <td>Kenyatta Market</td>
                <td>0740000569</td>
                <td>japhethofficial@gmail.com</td>
            </tbody>
        </table>
        <br><br>
        <!-- End of the table  -->

        <h4>Registration Form</h4>
        <form action="" method="">
        <label for="name">First Name:</label>
        <input type="text" id="fname" name="student_name" required>
        <label for="name">Last Name</label>
        <input type="text" id="lname" name="student_name" required>
        <br><br>

        <label for="Date">Date of birth</label>
        <input type="date" id="date_of_birth" name="date_of_birth">
        <br><br>

        <label for="email">Email address:</label>
        <input type="text" id="email" name="email" required>
        <br><br>

        <label for="password">Password:</label>
        <input type="password" name="password" minlength="8" maxlength="20">
        <br><br>

        <label for="Country">Country</label>
        <select type="text" id="country">
        <option>--select country--</option>
        <option value="Kenya">Kenya</option>
        <option value="Tanzania">Tanzania</option>
        <option value="Uganda">Uganda</option>
        <option value="Djibout">Djibout</option>
        <option value="Rwanda">Rwanda</option>
        </select>
        <br><br>

        <label for="gender">Gender:</label>
        <input type="radio" id="gender" name="gender" value="female">Female
        <input type="radio" id="gender" name="gender" value="male">Male
        <br><br>

        <label for="hobbies">Hobbies:</label>
        <input type="checkbox" id="hobbies" name="sports" value="Basketball">Basketball
        <input type="checkbox" id="hobbies" name="sports" value="Music">Music
        <input type="checkbox" id="hobbies" name="sports" value="Art">Art
        <input type="checkbox" id="hobbies" name="sports" value="Travel">Travel
        <br><br>

        <button>Register</button>
        <input type="button"   value="Cancel">
        <br><br>

        </form>
        <!-- End of the registration form-->

    </body>
</html>
