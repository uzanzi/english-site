<script setup>
import Projet from '../components/Projet.vue';
</script>

<template>
  <div class="container">
    <div class="grid">
      <div class="projet">
        <h1>internship BTS 1</h1>
        <Projet src="/assets/img/menu-babaz.png" alt="internship bts 1" />
        <div class="desc">
          <p>My first internship lasted six weeks. It was part of my first year of bts.
            The company that welcomed me was a freelancer and he's name was Logan Michel.
            I had to work at his home because he had no premises.
            During this internship, I used frameworks such as vuejs or tailwind.
            My goal was the following: Michel Logan had an application that used outdated technologies. He wanted me to
            help him deliver the app with modern technologies.</p>
        </div>
      </div>
      <div class="projet">
        <h1>internship BTS 2</h1>
        <div class="desc">
          <p>My second internship also lasted 6 weeks. It was part of my second year of bts.

            I went to do my internship in the company where my brother works. I had to cross France and live with my
            brother to do it. However, this internship was during the covid period. I had to do 3 weeks of teleworking.
            It wasn't very good to start the internship because I had to learn a framework that I didn't know. But my
            brother and his work colleagues helped me a lot and I thank them.

            The goal was to create a web application for employee arrivals and departures. She took the time of arrival
            and departure of employees, but also calculated their break times.

            To conclude, this internship brought me a lot of knowledge. I was able to discover the world of work.
          </p>
        </div>
        <Projet src="/assets/img/saisie-presence-start.png" alt="internship bts 2" />
      </div>
      <div class="projet">
        <h1>Challenge BTS 1</h1>
        <Projet src="/assets/img/challenge-sio1-accueil.PNG" alt="projet bts sio 1" />
        <div class="desc">
          <p>This project was a challenge for my first year of bts. We had to make a game in pairs over a period of one
            week and controlled by my teacher. The goal was to bring down balls of different colors and click on the color
            indicated by the instructions. There were 5 levels. To pass a level, you had to click 10 times on the right
            color. The more we advanced in the levels, the faster the speed of the balls went.
          </p>
        </div>
      </div>
      <div class="projet">
        <h1>Challenge BTS 2</h1>
        <div class="desc">
          <p>This project was a challenge for my second year of bts.
            This challenge was also to be done in pairs. The goal was to create a web application that registers all the
            devices of high school students.We used PHP and a mysql database to carry out this project. As a result, there
            were 2 gift cards worth €50 at fnac and we won !
          </p>
        </div>
        <Projet src="/assets/img/challenge-sio2-accueil.PNG" alt="projet bts sio 2" />
      </div>
      <div class="projet">
        <h1>Project vuejs License</h1>
        <Projet src="/assets/img/vuejs-membres.PNG" alt="Co'op projet vue js" />
        <div class="desc">
          <p>This project was carried out in order to discover the vuejs framework. We had to create a web application
            where we can create conversations and send messages in it. We had to learn how to make requests to an API. I
            liked this project because I learned a lot of things.
          </p>
        </div>
      </div>
      <div class="projet">
        <h1>image gallery project</h1>
        <div class="desc">
          <p>This project was to be carried out in groups of 3. I was with Cyprien Cotinaut and Teddy Clement Dels
            and it lasted a week. The goal was to create a web application of gallery of images. A user could log in,
            create
            galleries and add his photos to them. He had the option to share this gallery or not. There were public
            galleries where everyone could see the photos in this gallery. We did it with the vuejs framework because we
            found it easy to use and appropriate for this type of project.
          </p>
        </div>
        <Projet src="/assets/img/atelier-tuc-accueil.PNG" alt="Atelier CIASIE 1" />
      </div>
      <div class="projet">
        <h1>Project SCUDO</h1>
        <Projet src="/assets/img/scudo.PNG" alt="Project SCUDO" />
        <div class="desc">
          <p>The first project we had to do for the license was the "video stream". We were 6 on this project, but
            unfortunately a classmate stopped the training. The goal of this project was to be able to film with the
            application and record it in real time on a remote server because if we film and the video is not recorded on
            a server and the phone breaks, the video is lost. This video would then be available at any time on his
            account. Like image gallery project, user can share their video online. We liked this project because today
            there are a lot of demonstrations and many phones are broken during them. We named the project scudo, which
            means shield in Italian
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
h1 {
  text-align: center;
  font-family: Arial, Helvetica, sans-serif;
}

.container {
  display: flex;
  justify-content: center;
}

.grid {
  display: grid;
  grid-template-columns: 1fr;
  width: 95%;

  p {
    font-size: 20px;
    margin: 0 5px;
  }

  .projet {
    display: grid;
    grid-template-columns: 1fr 1fr;
    width: 100%;
    background-color: white;
    margin: 5px 0;

    h1 {
      grid-column: span 2;
      width: 100%;
    }
  }

  .desc {
    display: flex;
    margin: 5px;
    background-color: white;
    box-shadow: 1px 1px 12px #555;
    justify-content: center;
    align-items: center;
    text-align: center;
  }
}

@media screen and (max-width: 1380px) {
  .container {
    grid-template-columns: 1fr 1fr;
  }
}

@media screen and (max-width: 919px) {
  .container {
    grid-template-columns: 1fr;
  }
}
</style>

4-5 project
said why, when, with who ?
