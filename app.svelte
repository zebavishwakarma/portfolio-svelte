<!-- App.svelte -->
<script>
    // Import any necessary modules here
</script>

<style>
    /* Add your CSS styles here */
    body {
        font-family: 'Arial', sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f5f5f5;
    }

    header {
        background-color: #007bff; /* Matching shade of blue */
        color: #fff;
        padding: 1.5rem 0;
        text-align: center;
    }

    header h1 {
        font-size: 2.5rem;
        font-weight: bold;
        text-transform: uppercase;
        letter-spacing: 2px;
    }

    .container {
        max-width: 800px;
        margin: 0 auto;
        padding: 2rem;
    }

    .intro {
        text-align: center;
        margin-bottom: 2rem;
    }

    .profile {
        text-align: center;
        margin-bottom: 2rem;
    }

    .profile img {
        border-radius: 50%;
        width: 150px;
        height: 150px;
        object-fit: cover;
        border: 4px solid #333;
    }

    .about-me {
        background-color: #fff;
        padding: 2rem;
        border-radius: 8px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    .about-me p {
        font-size: 1.1rem;
        font-weight: 600;
        margin-bottom: 1.5rem;
    }

    .skills {
        margin-top: 2rem;
    }

    .skill {
        display: inline-block;
        background-color: #007bff;
        color: #fff;
        padding: 0.5rem 1rem;
        border-radius: 4px;
        margin-right: 0.5rem;
        font-size: 0.9rem;
        font-weight: 600;
    }

    .experience {
        margin-top: 2rem;
    }

    .experience p {
        font-size: 1.1rem;
        font-weight: 600;
        margin-bottom: 1rem;
    }

    .education {
        margin-top: 2rem;
    }

    .education p {
        font-size: 1.1rem;
        font-weight: 600;
        margin-bottom: 1rem;
    }

    .contact {
        text-align: center;
        margin-top: 2rem;
    }

    .contact p {
        font-size: 1.1rem;
        font-weight: 600;
        margin-bottom: 1rem;
    }

    .contact a {
        color: #bbe6ff; /* Lighter shade of blue */
        text-decoration: none;
        font-size: 1.1rem;
        font-weight: bold;
        margin: 0 0.5rem;
    }

    footer {
        text-align: center;
        padding: 1rem 0;
        background-color: #007bff; /* Matching shade of blue */
        color: #fff;
    }
</style>

<header>
    <h1>&copy; 2024 Prof. Zeba Vishwakarma Portfolio</h1>
</header>

<div class="container">
    <div class="intro">
        <h2>Welcome to my portfolio!</h2>
        <p>Hi everyone, I'm Prof. Zeba Vishwakarma, a Certified Educator in Data Analytics in Alteryx, and an Assistant Professor in Computer Science Engineering. I am passionate about teaching and research.</p>
    </div>

    <div class="profile">
        <!-- You can replace "profile.jpg" with your own photo -->
        <img src="zeba.jfif" alt="Profile Photo">
    </div>

    <div class="about-me">
        <h2>About Me</h2>
        <p>My expertise and area of interest include:</p>
        <ul>
            <li>Object Oriented Programming</li>
            <li>Operating Systems</li>
            <li>Python Programming</li>
            <li>Software Engineering</li>
            <li>Database Management Systems</li>
        </ul>
    </div>

    <div class="experience">
        <h2>Work Experience</h2>
        <p><strong>(Feb 2023- present)</strong> Assistant Professor - Department of Computer Science Engineering, Baderia Global Institute of Engineering and Management</p>
        <p><strong>(Dec 2021- Feb 2023)</strong> Assistant Professor - Department of Computer Science Engineering, SGBM Institute of Technology and Science</p>
    </div>

    <div class="education">
        <h2>Education</h2>
        <p><strong>M.Tech</strong> in Computer Science Engineering - Shri Ram Institute of Technology, Jabalpur, MP, India</p>
        <p><strong>Diploma</strong> in Computer Science Engineering - Kalaniketan Polytechnic College, Jabalpur, MP, India</p>
    </div>

    <div class="contact">
        <h2>Contact Me</h2>
        <p>Feel free to connect with me:</p>
        <a href="mailto:zeba.cs@global.org.in">Email</a> |
        <a href="https://github.com/zebavishwakarma>GitHub</a> |
        <a href="https://www.linkedin.com/in/zeba-khan-980905176/">LinkedIn</a>
    </div>
</div>
