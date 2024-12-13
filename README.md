
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
        <img src="Messenger_creation_2C94ACB3-AF07-4AEF-8CA2-B5FF3D79B0BD.jpeg" alt="Example illustration">
        <p>An example image illustrating cybersecurity concepts.</p>
        <h3>Video Example</h3>
            <iframe width="560" height="315" 
        src="https://www.youtube.com/embed/Yr0xPVFcf-U?pp=ygUOY3liZXIgc2VjdXJpdHk%3D" 
        title="YouTube video player" frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen>
</iframe>
        <p>A video demonstrating computer security practices.</p>
        <h3>Audio Example</h3>
        <audio controls>
            <source src="videoplayback (9).webm" type="audio/mp3">
            Your browser does not support the audio element.
        </audio>
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
