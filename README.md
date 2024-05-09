<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pankaj Pandey</title>
<style>
  @keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
  }

  body {
    font-family: Arial, sans-serif;
    animation: fadeIn 2s ease-in-out;
  }

  .container {
    max-width: 600px;
    margin: 0 auto;
    padding: 20px;
  }

  .profile {
    text-align: center;
  }

  .profile img {
    border-radius: 50%;
    animation: fadeIn 2s ease-in-out;
  }

  .profile h1,
  .profile h3 {
    animation: fadeIn 2s ease-in-out;
  }

  .social-icons img,
  .tools img {
    margin: 10px;
    filter: grayscale(100%);
    transition: filter 0.3s ease-in-out;
  }

  .social-icons img:hover,
  .tools img:hover {
    filter: none;
  }
</style>
</head>
<body>
<div class="container">
  <div class="profile">
    <img src="https://via.placeholder.com/150" alt="Profile Picture">
    <h1>Hi 👋, I'm Pankaj Pandey</h1>
    <h3>A passionate Backend developer from India</h3>
  </div>

  <ul class="social-icons">
    <li><a href="https://linkedin.com/in/https://www.linkedin.com/in/pankaj-pandey-39b851134" target="_blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40"></a></li>
    <li><a href="https://www.leetcode.com/https://leetcode.com/u/pp843958/" target="_blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="LeetCode" height="30" width="40"></a></li>
  </ul>

  <h3>Languages and Tools:</h3>
  <div class="tools">
    <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="Arduino" width="40" height="40">
    <img src="https://www.vectorlogo.zone/logos/microsoft_azure/microsoft_azure-icon.svg" alt="Azure" width="40" height="40">
    <!-- Add more images for tools and languages -->
  </div>
</div>
</body>
</html>
