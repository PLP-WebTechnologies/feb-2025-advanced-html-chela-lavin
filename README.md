<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Comprehensive Webpage</title>
</head>
<body>

    <header>
        <h1>Welcome to Our Site</h1>
        <p>Exploring various HTML elements.</p>
    </header>

    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>

    <main>
        <section>
            <h2>Ordered List (Roman Numerals)</h2>
            <ol type="I">
                <li>First item</li>
                <li>Second item</li>
                <li>Third item</li>
                <li>Fourth item</li>
                <li>Fifth item</li>
            </ol>
        </section>

        <section>
            <h2>External Image</h2>
            <img src="https://images.pexels.com/photos/2098085/pexels-photo-2098085.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="A scenic landscape">
            <p><small>Image courtesy of Pexels.com</small></p>
        </section>

        <section>
            <h2>Contact Information</h2>
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
                        <td>222 Willow Dr, Herecity</td>
                        <td>+254 744 444 444</td>
                        <td>bob.green@example.com</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <section>
            <h2>Registration Form</h2>
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
                    <input type="password" id="password" name="password" placeholder="Enter your password" required minlength="8">
                </div>

                <div>
                    <label for="birthdate">Date of Birth:</label>
                    <input type="date" id="birthdate" name="birthdate">
                </div>

                <div>
                    <label for="country">Country:</label>
                    <select id="country" name="country">
                        <option value="" disabled selected>Select your country</option>
                        <option value="ke">Kenya</option>
                        <option value="ug">Uganda</option>
                        <option value="tz">Tanzania</option>
                        <option value="other">Other</option>
                    </select>
                </div>

                <div>
                    <span>Gender:</span>
                    <label>
                        <input type="radio" name="gender" value="male" required> Male
                    </label>
                    <label>
                        <input type="radio" name="gender" value="female" required> Female
                    </label>
                    <label>
                        <input type="radio" name="gender" value="other" required> Other
                    </label>
                </div>

                <div>
                    <span>Interests:</span>
                    <label>
                        <input type="checkbox" name="interests" value="sports"> Sports
                    </label>
                    <label>
                        <input type="checkbox" name="interests" value="music"> Music
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
        </section>
    </main>

    <footer>
        <p>&copy; 2025 My Comprehensive Webpage. All rights reserved.</p>
        <p>Contact us at: <a href="mailto:info@example.com">info@example.com</a></p>
    </footer>

</body>
</html>ons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨
