<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Awesome Webpage</title>
</head>
<body>
    <h1>Welcome to My Page!</h1>

    <h2>Things to Do:</h2>
    <ol type="I">
        <li>Learn HTML</li>
        <li>Master CSS</li>
        <li>Explore JavaScript</li>
        <li>Build cool projects</li>
    </ol>

    <h2>Beautiful Image:</h2>
    <img src="https://images.pexels.com/photos/20787/pexels-photo.jpg?auto=compress&cs=tinysrgb&fit=crop&h=300&w=400" alt="A scenic landscape" width="400" height="300">

    <h2>Contact Information:</h2>
    <table>
        <thead>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>John Doe</td>
                <td>123 Main St, Anytown</td>
                <td>+254 700 000 000</td>
                <td>john.doe@example.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Oak Ave, Someville</td>
                <td>+254 711 111 111</td>
                <td>jane.smith@example.com</td>
            </tr>
            <tr>
                <td>Peter Jones</td>
                <td>789 Pine Ln, Othercity</td>
                <td>+254 722 222 222</td>
                <td>peter.jones@example.com</td>
            </tr>
            <tr>
                <td>Alice Brown</td>
                <td>101 Elm Rd, Nowhere</td>
                <td>+254 733 333 333</td>
                <td>alice.brown@example.com</td>
            </tr>
            <tr>
                <td>Bob Green</td>
                <td>222 Willow Dr, Hereville</td>
                <td>+254 744 444 444</td>
                <td>bob.green@example.com</td>
            </tr>
        </tbody>
    </table>

    <h2>Registration Form:</h2>
    <form action="#" method="POST">
        <div>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Your full name" required>
        </div>

        <div>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Your email address" required>
        </div>

        <div>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter password" required minlength="8">
        </div>

        <div>
            <label for="birthdate">Date of Birth:</label>
            <input type="date" id="birthdate" name="birthdate">
        </div>

        <div>
            <label for="occupation">Occupation:</label>
            <select id="occupation" name="occupation">
                <option value="" disabled selected>Select your occupation</option>
                <option value="student">Student</option>
                <option value="engineer">Engineer</option>
                <option value="developer">Developer</option>
                <option value="designer">Designer</option>
                <option value="other">Other</option>
            </select>
        </div>

        <div>
            <p>Gender:</p>
            <label>
                <input type="radio" name="gender" value="male"> Male
            </label>
            <label>
                <input type="radio" name="gender" value="female"> Female
            </label>
            <label>
                <input type="radio" name="gender" value="other"> Other
            </label>
        </div>

        <div>
            <p>Interests:</p>
            <label>
                <input type="checkbox" name="interests" value="coding"> Coding
            </label>
            <label>
                <input type="checkbox" name="interests" value="design"> Design
            </label>
            <label>
                <input type="checkbox" name="interests" value="reading"> Reading
            </label>
            <label>
                <input type="checkbox" name="interests" value="travel"> Travel
            </label>
        </div>

        <button type="submit">Register</button>
    </form>

    <footer>
        <p>&copy; 2025 My Awesome Webpage</p>
    </footer>
</body>
</html>
