<template>
  <div class="container">
    <div class="image-container">
      <img src="assets/img/Snapchat-442002958.jpg" alt="photo de Ugo Zanzi">
    </div>
    <div class="text">
      <h1>
        Hello everyone and welcome to my profile !
      </h1>
      <div id="presentation">
        <h2>Presentation</h2>
        <ul>
          <li>
            <p>My name is Ugo Zanzi, i'm 20 years old and I come from the Vogses in France.</p>
            <ul>
              outside the school, i do :
              <li>
                Sport (Football, tennis)
              </li>
              <li>
                chess
              </li>
              <li>
                video games
              </li>
            </ul>
          </li>
        </ul>
        <p>
          I'm actually in a 2-year degree at the university of Lorraine. I came to Nancy for my
          studies. When i was young, i didn't really what i want to do in the future. But my brothers were in the
          developpment and when they showed me their project, i was curious and and interested by what they were doing.
        </p>
      </div>
      <div id="education">
        <h2>Education</h2>
        <ul>
          <li>
            <h3>University Institute of Technology Nancy Charlemage, Nancy, 54000</h3>
            Bachelor's degree CIASIE.
          </li>
          <li>
            <h3>High School Frédéric Chopin, Nancy, 54000</h3>
            BTS SIO option SLAM and obtaining with an average of 14,47/20
          </li>
          <li>
            <h3>High School George Baumont, Saint-Dié-Des-Vosges, 88100</h3>
            Final year STI2D option SIN and obtaining the technological baccalaureate with honors
          </li>
          <li>
            <h3>Secondary school de la Haute Meurthe, Fraize, 88230</h3>
            3rd grade secondary school and obtaining the college patent, with honors
          </li>
        </ul>
      </div>
      <div id="skills">
        <h2>Skills</h2>
        <p>
          I am proficient in HTML, CSS, and JavaScript for building interactive and dynamic web pages. I also have a
          background in PHP for backend development and database management. I have worked with frameworks such as
          Symfony and Slim to create fast and efficient web applications. Additionally, I have experience in mobile app
          development with Flutter, allowing me to build cross-platform mobile applications. I have already use Bootstrap
          to facilitate responsive design for my web projects. Furthermore, I have experience in using Git and Github for
          version control and collaboration in software development projects. Finally, I have a good understanding of
          containerization and deployment using Docker to ensure consistent and reliable application deployment.
          Finally, I am proficient in Vue.js for building scalable and reactive user interfaces for web applications.
        </p>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container {
  margin: 10px;
  display: flex;
  font-size: 16px;
  color: black;

  .image-container {
    width: 21.4%;
  }

  img {
    width: 100%;
    object-fit: cover;
  }

  .text {
    flex: 1;
    text-align: center;
    padding: 0 10px;
    background-color: white;
    box-shadow: 1px 1px 12px #555;
    margin-left: 10px;
    height: auto;
    width: 75%;

    ul {
      padding: 0;

      li {
        list-style-type: none;
      }
    }
  }
}
</style>
