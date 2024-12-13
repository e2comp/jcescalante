
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lab Exercises</title>
    <style>
        body {
            background-color: #ADD8E6; /* Light blue background */
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
        }
        header {
            text-align: center;
            font-size: 24px;
            font-weight: bold;
            margin-bottom: 10px;
        }
        .author {
            text-align: center;
            font-size: 16px;
            margin-bottom: 20px;
            font-style: italic;
        }
        .welcome-message {
            text-align: center;
            font-size: 18px;
            margin-bottom: 20px;
            color: #333;
        }
        .container {
            border: 2px solid black;
            padding: 20px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        table, th, td {
            border: 1px solid black;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
        .form-container {
            margin-top: 20px;
        }
        img, video, audio {
            display: block;
            margin: 20px auto;
            max-width: 100%;
            border: 2px solid black;
        }
    </style>
</head>
<body>
    <header>Lab Exercises</header>
    <div class="author">By: Julius Cesar Escalante</div>
    <div class="welcome-message">
        Welcome to the Lab Exercises! Explore key topics like plagiarism, malware, and more while learning to create web pages.
    </div>
    <div class="container">
        <h2>Plagiarism</h2>
        <p>
            Plagiarism is the act of using someone else's work without giving them proper credit. It can lead to severe consequences such as academic penalties, fines, or legal actions. Below are some reported cases of plagiarism:
        </p>
        <table>
            <thead>
                <tr>
                    <th>Case</th>
                    <th>Country</th>
                    <th>Punishment</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Student copying research papers</td>
                    <td>USA</td>
                    <td>Failing grade, expulsion</td>
                </tr>
                <tr>
                    <td>Corporate data theft</td>
                    <td>India</td>
                    <td>Fines up to ₹10 lakhs</td>
                </tr>
                <tr>
                    <td>Book plagiarism</td>
                    <td>UK</td>
                    <td>Lawsuit, heavy fines</td>
                </tr>
            </tbody>
        </table>
        <h2>Malware, Antivirus, Virus, and Spam</h2>
        <p>
            Malware is malicious software designed to harm, disrupt, or exploit systems. Viruses are a type of malware that replicate by attaching themselves to files. Spam refers to unsolicited messages, often used for advertising or phishing.
        </p>
        <h2>Multimedia Examples</h2>
        <h3>Image Example</h3>
        <img src="https://via.placeholder.com/600x300" alt="Example illustration">
        <p>An example image illustrating cybersecurity concepts.</p>
        <h3>Video Example</h3>
        <video controls>
            <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
        <p>A video demonstrating computer security practices.</p>
        <h3>Audio Example</h3>
        <audio controls>
            <source src="https://www.w3schools.com/html/horse.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
        <p>An audio clip providing insights into malware prevention.</p>
    </div>
    <div class="form-container">
        <h2>Feedback Form</h2>
        <form>
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name" required><br><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" required><br><br>
            <label for="topic">Topic:</label><br>
            <select id="topic" name="topic">
                <option value="plagiarism">Plagiarism</option>
                <option value="malware">Malware</option>
                <option value="spam">Spam</option>
            </select><br><br>
            <label for="comments">Comments:</label><br>
            <textarea id="comments" name="comments" rows="4" cols="50"></textarea><br><br>
            <input type="submit" value="Submit">
        </form>
    </div>
</body>
</html>
