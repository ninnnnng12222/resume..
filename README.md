<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Resume</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 0;
    }

    .container {
      max-width: 900px;
      margin: 30px auto;
      background: #fff;
      padding: 30px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .header {
      text-align: center;
      margin-bottom: 30px;
    }

    .header img {
      width: 150px;
      height: 150px;
      object-fit: cover;
      border-radius: 10px;
      border: 2px solid #ccc;
    }

    h1 {
      margin: 15px 0 5px;
      font-size: 28px;
    }
	
	    .skill-img {
      width: 30px;
      height: 30px;
      vertical-align: middle;
      margin-right: 10px;
    }

    .contact-info {
      font-size: 14px;
      color: #555;
    }

    section {
      margin-top: 25px;
    }

    h2 {
      color: #2c3e50;
      border-bottom: 2px solid #ddd;
      padding-bottom: 5px;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    li {
      margin-bottom: 10px;
    }

    .info-table {
      width: 100%;
      border-collapse: collapse;
    }

    .info-table td {
      padding: 8px;
      vertical-align: top;
    }

    .info-table td.label {
      font-weight: bold;
      width: 200px;
      color: #333;
    }

    .reference {
      display: flex;
      align-items: center;
      margin-bottom: 20px;
    }

    .reference img {
      width: 60px;
      height: 60px;
      border-radius: 50%;
      object-fit: cover;
      margin-right: 15px;
    }

    .reference-details {
      font-size: 14px;
    }

    .certificate {
      margin-bottom: 10px;
    }
  </style>
</head>
<body>
  <div class="container">
    
    <!-- Header with ID Image -->
    <div class="header">
      <img src="C:\Users\Admin\Desktop\web\5b6617cd-d15c-4c32-b0dd-826dd9707819.jpg" alt="ID Photo">
      <h1>Dustin B. Belonio</h1>
      <div class="contact-info">
        <p>9B Blanco Compound Santulan Malabon City</p>
        <p>Contact: 09467217117 | Email: dustinbelonio655@gmail.com</p>
      </div>
    </div>

    <!-- Objective -->
    <section>
      <h2>Objective / Purpose of Application</h2>
      <p>To obtain a position as a Junior Web Developer where I can apply my skills in web technologies and grow in a dynamic environment.</p>
    </section>

    <!-- IT Skills -->
    <section>
      <h2>IT-Related Skills</h2>
      <ul>
      <li><img class="skill-img" src="https://cdn-icons-png.flaticon.com/512/732/732212.png" alt="HTML Icon"> HTML5</li>
      <li><img class="skill-img" src="https://cdn-icons-png.flaticon.com/512/732/732190.png" alt="CSS Icon"> CSS3</li>
      <li><img class="skill-img" src="https://cdn-icons-png.flaticon.com/512/5968/5968292.png" alt="JavaScript Icon"> JavaScript</li>

      </ul>
    </section>

    <!-- Additional Information -->
    <section>
      <h2>Additional Information</h2>
      <table class="info-table">
        <tr>
          <td class="label">Nickname:</td>
          <td>Tin</td>
        </tr>
        <tr>
          <td class="label">Birthday:</td>
          <td>November 10, 2006</td>
        </tr>
        <tr>
          <td class="label">Age:</td>
          <td>18</td>
        </tr>
        <tr>
          <td class="label">Religion:</td>
          <td>Christian</td>
        </tr>
        <tr>
          <td class="label">Nationality:</td>
          <td>Filipino</td>
        </tr>
        <tr>
          <td class="label">Height:</td>
          <td>5'5</td>
        </tr>
        <tr>
          <td class="label">Weight:</td>
          <td>85kg</td>
        </tr>
      </table>
    </section>

    <!-- Education -->
    <section>
      <h2>Educational Background</h2>
      <ul>
        
		<li><strong>Bachelor of Science in Information Technology</strong><br>Global Reciprocal Colleges, 2024-2026</li>
         <li><strong>Senior High School:</strong> Panghulo National High School, 2021-2023</li>
		<li><strong>High School:</strong> Panghulo National High School, 2017–2021</li>
		
      </ul>
    </section>

    <!-- Certificates and Awards -->
    <section>
      <h2>Certificates & Awards</h2>
      <div class="certificate">
        <strong>Certificate Of Work Immersion</strong><br>
        Issued by Iballe – March 2021
      </div>
    </section>

    <!-- Work Experience -->
    <section>
      <h2>Working Experience</h2>
      <ul>
        <li>
          <strong>staff</strong><br>
          crew | June 2023 – Dec 2023<br>
          Work on Jollibee Crew and Staff
		   
        </li>
      </ul>
    </section>

    <!-- Character References -->
    <section>
      <h2>Character References</h2>

      <div class="reference">
        <img src="https://via.placeholder.com/60" alt="Reference 1">
        <div class="reference-details">
          <strong>Example 1</strong><br>
          Hacker, Boy Corp<br>
          Email: Belonio.com<br>
          Phone: +123 456 7891
        </div>
      </div>

      <div class="reference">
        <img src="https://via.placeholder.com/60" alt="Reference 2">
        <div class="reference-details">
          <strong>Example 2</strong><br>
          Krusty Crab, <br>
          Email: dustin.com<br>
          Phone: +123 456 7892
        </div>
      </div>

      <div class="reference">
        <img src="https://via.placeholder.com/60" alt="Reference 3">
        <div class="reference-details">
          <strong>example3</strong><br>
          IT Instructor, EME University<br>
          Email: GRC.example<br>
          Phone: +123 456 7893
        </div>
      </div>

    </section>
  </div>
</body>
</html>
