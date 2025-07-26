
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Jay's Portfolio</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>
  <div class="container">
    <header>
      <h1>Jay's Portfolio</h1>
      <p class="sub">Seth Oche Jesse – Digital Artist & Student</p>
    </header>

    <section>
      <h2>About Me</h2>
      <p>
        Hello! My name is Seth Oche Jesse (Jay), a digital artist and Computer Science student at the University of Abuja. I enjoy creating visual work that expresses emotions, culture, and unique perspectives. This portfolio showcases my creative journey so far.
      </p>
    </section>

    <section>
      <h2>Past Work</h2>
      <p>Here are some of my past projects. These represent earlier designs and creative works I've completed.</p>
      <div class="gallery" id="past-gallery">
        <!-- Uploaded past work will appear here -->
         <img src="/black-widow-2.jpg" alt="black widow">
         <img src="/doctor strange in the multiverse of madness 3.jpg" alt="doctor strange">
      </div>
    </section>

    <section>
      <h2>Present Work</h2>
      <p>These are the projects I'm currently working on. I'm exploring new ideas and improving my skills daily.</p>
      <div class="gallery" id="present-gallery">
        <!-- Uploaded present work will appear here -->
         <img src="/bellerina11.jpg" alt="ballerina">
         <img src="/fantastic four.jpg" alt="fantastic 4">
      </div>
    </section>

    <section>
      <h2>Future Plans</h2>
      <p>
        In the future, I hope to:
        <ul>
          <li>Keep improving as a digital artist</li>
          <li>Start selling my artworks</li>
          <li>Become recognized globally</li>
          <li>Work with movie companies like Marvel or Disney</li>
        </ul>
      </p>
    </section>

    <footer>
      <p>© 2025 Jay | All rights reserved</p>
    </footer>
  </div>

  <!-- This script allows ONLY YOU to upload images manually when editing -->
  <!-- <script>
    const pastImages = [
      // Add paths to past images here
      "images/past1.jpg",
      "images/past2.jpg"
    ];

    const presentImages = [
      // Add paths to present images here
      "images/present1.jpg",
      "images/present2.jpg"
    ];

    function displayImages(imageList, containerId) {
      const container = document.getElementById(containerId);
      imageList.forEach(src => {
        const img = document.createElement("img");
        img.src = src;
        img.alt = "Project image";
        container.appendChild(img);
      });
    }

    displayImages(pastImages, "past-gallery");
    displayImages(presentImages, "present-gallery");
  </script> -->
</body>
</html>
