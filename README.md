Gallerly.js
-----------

![Screenshot](screenshot.png)

Usage
-----

HTML

    <div id="gallerly" class="container">
      <h1>NASA Space Gallery</h1>
      <div class="image-viewer">
        <a class="thumbnail"><img src="images/mmupack.gif" data-title="NASA Earth Image" data-description="Earth, also called the world[n 5] (and, less frequently, Gaia[n 6] or, in Latin, Terra[26]), is the third planet from the Sun, the densest planet in the Solar System, the largest of the Solar System's four terrestrial planets, and the only astronomical object known to accommodate life. The earliest life on Earth arose at least 3.5 billion years ago."/></a>
        <a class="thumbnail"><img src="images/NASA-Space-Shuttle.jpg" data-title="NASA Earth Image" data-description="Earth, also called the world[n 5] (and, less frequently, Gaia[n 6] or, in Latin, Terra[26]), is the third planet from the Sun, the densest planet in the Solar System, the largest of the Solar System's four terrestrial planets, and the only astronomical object known to accommodate life. The earliest life on Earth arose at least 3.5 billion years ago."/></a>
        <a class="thumbnail"><img src="images/sls-rocket-art.jpg"  data-title="NASA Earth Image" data-description="Earth, also called the world[n 5] (and, less frequently, Gaia[n 6] or, in Latin, Terra[26]), is the third planet from the Sun, the densest planet in the Solar System, the largest of the Solar System's four terrestrial planets, and the only astronomical object known to accommodate life. The earliest life on Earth arose at least 3.5 billion years ago."/></a>

        <a class="thumbnail"><img src="images/earth.jpeg" data-title="NASA Earth Image" data-description="Earth, also called the world[n 5] (and, less frequently, Gaia[n 6] or, in Latin, Terra[26]), is the third planet from the Sun, the densest planet in the Solar System, the largest of the Solar System's four terrestrial planets, and the only astronomical object known to accommodate life. The earliest life on Earth arose at least 3.5 billion years ago."/></a>
        <a class="thumbnail"><img src="images/9070851928_555c3a429e_b.jpg" data-title="NASA Earth Image" data-description="Earth, also called the world[n 5] (and, less frequently, Gaia[n 6] or, in Latin, Terra[26]), is the third planet from the Sun, the densest planet in the Solar System, the largest of the Solar System's four terrestrial planets, and the only astronomical object known to accommodate life. The earliest life on Earth arose at least 3.5 billion years ago."/></a>
        <a class="thumbnail"><img src="images/Des_M_1696838a.jpg" data-title="NASA Earth Image" data-description="Earth, also called the world[n 5] (and, less frequently, Gaia[n 6] or, in Latin, Terra[26]), is the third planet from the Sun, the densest planet in the Solar System, the largest of the Solar System's four terrestrial planets, and the only astronomical object known to accommodate life. The earliest life on Earth arose at least 3.5 billion years ago."/></a>

        <a class="thumbnail"><img src="images/mar-mission.jpg" data-title="NASA Earth Image" data-description="Earth, also called the world[n 5] (and, less frequently, Gaia[n 6] or, in Latin, Terra[26]), is the third planet from the Sun, the densest planet in the Solar System, the largest of the Solar System's four terrestrial planets, and the only astronomical object known to accommodate life. The earliest life on Earth arose at least 3.5 billion years ago."/></a>
        <a class="thumbnail"><img src="images/mars-2.jpg" data-title="NASA Earth Image" data-description="Earth, also called the world[n 5] (and, less frequently, Gaia[n 6] or, in Latin, Terra[26]), is the third planet from the Sun, the densest planet in the Solar System, the largest of the Solar System's four terrestrial planets, and the only astronomical object known to accommodate life. The earliest life on Earth arose at least 3.5 billion years ago."/></a>
        <a class="thumbnail"><img src="images/mars.jpg" data-title="NASA Earth Image" data-description="Earth, also called the world[n 5] (and, less frequently, Gaia[n 6] or, in Latin, Terra[26]), is the third planet from the Sun, the densest planet in the Solar System, the largest of the Solar System's four terrestrial planets, and the only astronomical object known to accommodate life. The earliest life on Earth arose at least 3.5 billion years ago."/></a>

        <a class="thumbnail"><img src="images/p0140xss.jpg" data-title="NASA Earth Image" data-description="Earth, also called the world[n 5] (and, less frequently, Gaia[n 6] or, in Latin, Terra[26]), is the third planet from the Sun, the densest planet in the Solar System, the largest of the Solar System's four terrestrial planets, and the only astronomical object known to accommodate life. The earliest life on Earth arose at least 3.5 billion years ago."/></a>
        <a class="thumbnail"><img src="images/sls-rocket-art.jpg" data-title="NASA Earth Image" data-description="Earth, also called the world[n 5] (and, less frequently, Gaia[n 6] or, in Latin, Terra[26]), is the third planet from the Sun, the densest planet in the Solar System, the largest of the Solar System's four terrestrial planets, and the only astronomical object known to accommodate life. The earliest life on Earth arose at least 3.5 billion years ago."/></a>
        <a class="thumbnail"><img src="images/space_shuttle_launch.jpg" data-title="NASA Earth Image" data-description="Earth, also called the world[n 5] (and, less frequently, Gaia[n 6] or, in Latin, Terra[26]), is the third planet from the Sun, the densest planet in the Solar System, the largest of the Solar System's four terrestrial planets, and the only astronomical object known to accommodate life. The earliest life on Earth arose at least 3.5 billion years ago."/></a>
        <div class="preview hide">
          <div class="wrapper">
            <span class="arrow"></span>
            <a class="prev">&larr; Prev</a>
            <div class="preview-content">
              <img src="" />
              <div class="content">
                <h3 class="title"></h3>
                <span class="description"></span>
              </div>
            </div>
            <a class="next">Next &rarr;</a>
            <a class="close-preview">Close</a>
          </div>
      </div>
    </div>


JavaSript

    var $gallerly = document.querySelector("#gallerly");
    var gallerly = new Gallerly($gallerly);


Author
------
Abhinay Omkar
