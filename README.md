<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced HTML5 Elements and Forms</title>
</head>

<body>
    <!-- Ordered List with Roman Numerals -->
    <h2>My Ordered List</h2>
    <ol type="I">
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ol>

    <!-- External Image from Pexels -->
    <h2>External Image</h2>
    <img src="https://images.pexels.com/photos/1684463/pexels-photo-1684463.jpeg" alt="Beautiful landscape" width="600">

    <!-- Table of Contacts -->
    <h2>Contact List</h2>
    <table border="1" cellpadding="10" cellspacing="0">
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
                <td>123 Main St</td>
                <td>+123456789</td>
                <td>john@example.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Oak Ave</td>
                <td>+987654321</td>
                <td>jane@example.com</td>
            </tr>
            <tr>
                <td>Jim Brown</td>
                <td>789 Pine Rd</td>
                <td>+1122334455</td>
                <td>jim@example.com</td>
            </tr>
            <tr>
                <td>Lisa White</td>
                <td>101 Maple Dr</td>
                <td>+123098765</td>
                <td>lisa@example.com</td>
            </tr>
            <tr>
                <td>Tom Green</td>
                <td>202 Birch Blvd</td>
                <td>+2233445566</td>
                <td>tom@example.com</td>
            </tr>
        </tbody>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="/submit" method="POST">
        <!-- Name Field -->
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>

        <!-- Email Field -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

        <!-- Password Field -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter your password" required><br><br>

        <!-- Date Field -->
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required><br><br>

        <!-- Dropdown Menu -->
        <label for="country">Country:</label>
        <select id="country" name="country" required>
            <option value="usa">USA</option>
            <option value="uk">UK</option>
            <option value="india">India</option>
            <option value="canada">Canada</option>
        </select><br><br>

        <!-- Radio Buttons -->
        <label for="gender">Gender:</label>
        <input type="radio" id="male" name="gender" value="male" required>
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female" required>
        <label for="female">Female</label><br><br>

        <!-- Checkbox -->
        <label for="terms">I agree to the terms and conditions:</label>
        <input type="checkbox" id="terms" name="terms" required><br><br>

        <!-- Submit Button -->
        <input type="submit" value="Register">
    </form>

    <!-- Audio and Video Elements -->
    <h2>Multimedia Elements</h2>
    <!-- Audio Player -->
    <audio controls>
        <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mp3">
        Your browser does not support the audio element.
    </audio><br><br>

    <!-- Video Player -->
    <video width="320" height="240" controls>
        <source src="https://www.w3schools.com/html/movie.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</body>

</html>

