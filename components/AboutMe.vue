<template>
    <div class="about_me">
        <div class="about_me--title">
            <h2>Lorgio Roda</h2>
        </div>
        <div class="about_me--info">
            <p class="about_me--text">
                I'm Lorgio Roda, a frontend developer, passionate about learning and upgrading my skills every day. Loves to improve user experience, solve problems, build better products, scalable, maintainable and testable code.
            </p>
            <p class="about_me--text">
                Born in Bolivia and now living in Spain Barcelona. In 2020, I started my programming career in a self-taught way, also using learning platforms like Platzi and CodeCademy, at last I decided to study at Iron Hack Barcelona a full remote bootcamp for web developers.
            </p>
            <p class="about_me--text">
                Then I decided to leave my comfort zone and move to Spain. I was lucky to collaborate and work with very good teams, where I have developed and improved my technical and soft skills, now I want to face new challenges and never stop learning.
            </p>
        </div>
        <div></div>
        <div class="about_me--social">
            <a href="https://twitter.com/roda_lorgio" target="_blank">Twitter</a>
            <a href="https://www.linkedin.com/in/lorgio-roda-roca/" target="_blank">LinkedIn</a>
            <a href="mailto:lorgiorodaroca@gmail.com">Email</a>
        </div>
    </div>
</template>
<script>
export default {};
</script>
<style>
.about_me {
  display: flex;
  flex-direction: column;
  margin: 0px 3.2rem;
  font-size: 3vh;
}
.about_me h2 {
  min-height: 100px;
  margin: 0px 20px;
  color: #f1f3f9;
  font-size: 2.5rem;
  font-weight: 800;
  letter-spacing: 1.5px;
}
.about_me--title {
  margin: 40px 20px;
}
.about_me--info {
  max-width: 400px;
  height: 100%;
  margin: 40px 20px;
  font-weight: 300;
  color: #f1f3f9;
}
.about_me--text {
  margin: 10px;
  margin-top: 40px;
  font-size: 1.7rem;
  letter-spacing: 1.5px;
  text-align-last: auto;
  line-height: 28px;
}
.about_me--social {
  display: flex;
  max-width: 400px;
  align-items: center;
  justify-content: space-around;
  margin-top: 60px;
  margin: 0px 20px;
}
.about_me--social a {
  margin-bottom: 20px;
  font-size: 1.7rem;
  text-decoration: none;
  color: #f1f3f9;
}
@media (min-width: 1020px) {
  .about_me {
    display: grid;
    grid-template-columns: 1fr max-content;
    grid-template-rows: [row1-start] 1fr [row1-end] 1fr;
    height: 100vh;
  }
  .about_me--info {
    margin: 30px 20px;
    max-width: 600px;
  }
  .about_me--text {
    margin: 30px 20px;
    margin-bottom: 20px;
  }
  .about_me--social {
    max-width: 600px;
    justify-content: start;
  }
  .about_me--social a {
    margin: 0px 20px;
  }
  @media (min-width: 2120px) {
    .about_me--text {
      max-width: 900px;
    }
    .about_me--social {
      max-width: 900px;
    }
  }
}
</style>

