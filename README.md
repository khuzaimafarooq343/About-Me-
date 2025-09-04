<!Doctype html>
<html lang ="en">
    <head>
        <meta charset = "UTF-8">
        <title>
            My Portfolio
        </title>
    </head>
    <body>
        <a href = "https://github.com/khuzaimafarooq343/About-Me-.git">gitHub</a>
        <h2> Welcome To My Portfolio</h2>
        <img src="e:\my profile.jpg" alt = "My Profile Picture">
        <nav>
            <a href = "index.html">Home</a> |
            <a href = "about.html">About</a> |
            <a href = "project.html">Project</a> |
            <a href = "contact.html">Contact</a>
        </nav>
        <main>
            <h3> Hello! </h3>
            <p> I am Khuzaima Farooq from BSIT(3rd Semester). 
                I am a student and beginner in web development, learning how to create websites using HTML.
                I have just started my journey and this is my very first Project.
                As this is my first attempt, many things in this project are taken from Internet
                like video, audio as a sample.
             </p>

             <h3> Education</h3>
            <table border = "1" cellpadding = "10">
                <tr> 
                    <th> Year </th>
                    <th> Institute </th>
                    <th> Qualification</th>
                </tr>
                <tr>
                    <td> 2022 </td>
                    <td> Steps School System Chakwal </td>
                    <td> Matric </td>
                </tr>
                <tr>
                    <td> 2024 </td>
                    <td> Kips College Chakwal </td>
                    <td> F.S.C Pre-Engineering </td>
                </tr>
                <tr>
                    <td> Undergraduate </td>
                    <td> University Of Chakwal </td>
                    <td> BSIT(3rd Semester) </td>
                </tr>

            </table>

            <h3> The Way I See Myself </h3>
            <ul>
                <li> I am a learner who believes every small step counts. </li>
                <li> I believe mistakes are not failure, but lessons. </li>
                <li> I grow everyday. </li>
                <li> I value creativity that speaks to the heart. </li>
                <li> I am not perfect, but I am improving everyday. </li>
            </ul>

            <h3> My Heart's Playlist </h3>
            <ol>
                <li> Capturing Memories </li>
                <li> Spending time with nature </li>
                <li> Writing thoughts that carry deep meanings. </li>
                <li> Exploring new things </li>
                <li> Connecting with friends and sharing laughter. </li>
            </ol>

            <h3> Video Sample</h3>
            <video width = '250' height = '190' controls>
                <source src="c:\Users\FINE COMPUTERS\Downloads\Sample Video.mp4">
                Your browser doesn't support this video.
            </video>

            <h3> Audio Sample</h3>
            <audio controls>
                <source src="c:\Users\FINE COMPUTERS\Downloads\Sample Audio.mp3">
                Your browser doesn't support this audio.
            </audio>

            <h3> Get In Touch </h3>
            <form> 
                <label for = "Name">Name: </label> 
                <input type = "text" id = "Name"
                placeholder = "Enter your Full Name: "
                required>
                <br><br>

                <label for = "Email">Email: </label>
                <input type = "Email" id = "Email"
                placeholder = "Enter your Email ID: "
                required> 
                <br><br>

                <label for = "Phone Number">Phone Number</label>
                <input type = "Number" id = "Phone Number"
                placeholder = "Enter your contact number"
                required>
                <br><br>

                <label for = "Message">Message</label>
                <textarea id = "Message"></textarea>
                <br><br>

                <button type = "Submit">Submit</button>
                <button type = "Reset">Reset</button>
            </form>

        </main>
        <footer>
            <p> ©2025 About Khuzaima Farooq</p>
        </footer>
    </body>
</html>
