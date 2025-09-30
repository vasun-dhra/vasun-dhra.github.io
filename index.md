<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Professional Documents</title>
    
    <style>
        /* Basic styles for the entire page */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f7f6; 
            color: #333;
            line-height: 1.6;
            display: flex;
            justify-content: center;
        }

        /* Container to center the content and set max width */
        .container {
            width: 90%;
            max-width: 800px;
            margin: 40px auto;
            padding: 30px;
            background-color: #ffffff; 
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 8px; 
        }

        /* Styling for the main header */
        h1 {
            color: #2c3e50;
            text-align: center;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
            margin-bottom: 30px;
            font-weight: 300;
        }

        /* Styling for section headers */
        h2 {
            color: #34495e;
            margin-top: 25px;
            font-weight: 400;
        }

        /* Styling for the paragraphs (descriptions) */
        p {
            font-size: 1.1em;
            margin-bottom: 20px;
        }

        /* Styling for the photo container */
        .photo-container {
            text-align: center; /* Center the image */
            margin-bottom: 30px;
        }

        /* Styling for the profile photo */
        .profile-photo {
            width: 150px; /* Set a fixed size */
            height: 150px;
            border-radius: 50%; /* Makes the image perfectly round */
            object-fit: cover; /* Ensures the image covers the area without stretching */
            border: 4px solid #3498db; /* Blue border */
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
        }

        /* Styling for the links (the most important part) */
        a {
            color: #3498db;
            text-decoration: none;
            font-weight: bold;
            border-bottom: 2px dashed #3498db;
            transition: color 0.3s ease, border-bottom 0.3s ease;
            padding-bottom: 2px;
        }

        a:hover {
            color: #2980b9;
            border-bottom: 2px solid #2980b9;
        }
    </style>
</head>
<body>
    <div class="container">
        
        <div class="photo-container">
            <img src="photo.jpeg" alt="Profile Picture" class="profile-photo">
        </div>
        
        <h1>My Professional Documents</h1>

        <h2>Curriculum Vitae</h2>
        <p>
            Please view my latest professional curriculum vitae here: 
            <a href="Unige_CV.pdf" target="_blank">View CV (PDF)</a>
        </p>

        <hr> 

        <h2>Publications</h2>
        <p>
            View my published research paper here:
            <a href="publication_paper.pdf" target="_blank">View Research Paper (PDF)</a>
        </p>
    </div>
</body>
</html>