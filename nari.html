<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Student Portal</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f4f6f8;
      padding: 40px;
    }

    .container {
      max-width: 900px;
      margin: auto;
    }

    h1, h2 {
      color: #2c3e50;
    }

    .available-courses,
    .enrolled-courses,
    .progress,
    .certificates {
      background-color: white;
      border-radius: 8px;
      padding: 20px;
      margin-bottom: 30px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    }

    select, button {
      padding: 10px;
      font-size: 16px;
      margin-top: 10px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }

    .enrolled-list {
      list-style-type: none;
      padding-left: 0;
    }

    .enrolled-list li {
      margin-bottom: 5px;
    }

    .logout-btn {
      background-color: #e74c3c;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 4px;
      cursor: pointer;
    }

    .logout-btn:hover {
      background-color: #c0392b;
    }

    .cert-btn {
      background-color: #3498db;
      color: white;
      border: none;
      padding: 10px 16px;
      font-size: 16px;
      border-radius: 5px;
      text-decoration: none;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    .cert-btn:hover {
      background-color: #2980b9;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Welcome, Student!</h1>

    <div class="available-courses">
      <h2>Available Courses</h2>
      <select id="courseSelect">
        <option value="" disabled selected>Select a course</option>
        <option value="BSIS">BSIS</option>
        <option value="ACT">ACT</option>
        <option value="BSOM">BSOM</option>
      </select>
      <button onclick="enrollCourse()">Enroll</button>
    </div>

    <div class="enrolled-courses">
      <h2>Enrolled Courses</h2>
      <ul id="enrolledCourses" class="enrolled-list"></ul>
    </div>

    <div class="progress">
      <h2>Progress</h2>
      <p>You have completed <strong>75%</strong> of your courses.</p>
    </div>

    <div class="certificates">
      <h2>Certificates</h2>
      <a href="#" class="cert-btn" onclick="alert('Downloading...')">Print Certificate</a>
    </div>

    <button class="logout-btn" onclick="logout()">Logout</button>
  </div>

<script>
  const enrolledCourses = [];

  function enrollCourse() {
    const select = document.getElementById("courseSelect");
    const course = select.value;

    if (course && !enrolledCourses.includes(course)) {
      enrolledCourses.push(course);
      updateEnrolledList();
    } else {
      alert("Course already enrolled or not selected.");
    }
  }

  function updateEnrolledList() {
    const list = document.getElementById("enrolledCourses");
    list.innerHTML = "";

    for (let i = 0; i < enrolledCourses.length; i++) {
      list.innerHTML += "<li>" + enrolledCourses[i] + "</li>";
    }
  }

  function logout() {
    localStorage.removeItem("loggedInUser");
    window.location.href = "login.html";
  }

  const user = localStorage.getItem("loggedInUser");
  if (!user) {
    window.location.href = "login.html";
  }
</script>

</body>
</html>
