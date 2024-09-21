<script setup>
// import { RouterLink } from 'vue-router'
// import {  RouterView } from 'vue-router'
// import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="@/assets/images/website-BioKgo0U.png" />

    <div class="wrapper">
      <address>
        <span>Summit County, Colorado</span>
        <span>(719) 838-3915</span>
        <span>erin.stark@summitsproutstherapy.com</span>
      </address>
      <blockquote>
        “How we spend our days is, of course, how we spend our lives.” <br /> — Annie Dillard, The Writing Life
      </blockquote>
      <nav>
        <!-- <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink> -->
        <!-- <RouterLink to="{ path: '/#advocacy'}"> Advocacy </RouterLink> -->
        <a href="#advocacy">Advocacy</a>
      </nav>
    </div>
  </header>

  <body>
    <div id="about">
      <h1>About Me</h1>
      <p>Over the past 15 years as an occupational therapist I have worked with all age ranges, infancy to 90+ years
        old, in numerous settings (early intervention, schools, home health, hospitals, and skilled nursing facilities).
        I have supported clients with varied diagnoses such as ADHD, Sensory Processing Disorder, Autism, Down Syndrome,
        Prader Willi’s, Cerebral Palsy, Developmental Delay, Stroke, Head trauma, Dementia, Cardiac Issues, Orthopedic
        Injury, Aging in place and many more. What I have learned from all of these experiences is the importance of
        appreciating the skills and talents we have no matter our circumstances. As an occupational therapist, it has
        been my job and my joy to help support those in need to meet their goals of living independently and
        participating in their desired activities on a daily basis.</p>
      <aside>
        Fees: $120 an hour (this is about the middle between what I get for EI and Medicaid billing. It is also $20-30
        less then what other providers have for their consulting jobs–Counselor, PT in summit county→ so not competing
        for jobs)
      </aside>
    </div>

    <div></div>

    <div id="services">
      <h1>Services</h1>

      <div id="occupation-therapy" class="service">
        <h2>Occupational Therapy</h2>
        <p>The primary goal of occupational therapy is to ensure you can live independently and function in your daily
          life skills. This can apply from infancy all the way to age 90+. I support my clients through addressing their
          needs for motor skills, cognitive skills, social emotional skills, organizational skills, universal design
          support and sensory processing skills which can impact all areas of life. My goal in providing occupational
          therapy services is to help clients meet their goals to develop, recover, improve, and maintain skills needed
          for daily living.
        </p>
      </div>

      <div id="consulting" class="service">
        <h2> Consulting </h2>
        <p>
          For providers and caregivers there is nothing more important than ensuring the children or adults we care for
          are safe and have all of their needs met. As a consultant, I have developed various trainings to support in
          numerous settings such as daycares, schools and public settings focusing on sensory processing, self
          regulation and motor skills.
        </p>
        <h3 class="list">Services include:</h3>
        <ul>
          <li>Location specific trainings to meet their needs and concerns</li>
          <li>Instructional observations across settings</li>
          <li>1:1, small group and full staff trainings</li>
          <li>On going in class/ group support</li>
        </ul>
      </div>

      <div id="advocacy" class="service">
        <h2>Advocacy</h2>
        <p>
          As a parent, you always want to make sure your children are supported. Parents are the experts on their
          children and what needs they may have. Schools have many systems in place to support children at their own
          level. However understanding and learning what those supports are can be a challenge. Navigating the process
          of 504, IEP or other supports can be overwhelming. Having worked in various educational school systems for the
          past 13 years as well as gaining a Master’s of Education in Administration, I am well versed in the laws, and
          services a school can provide. Summit Sprouts has designed its services to correspond with the needs of our
          clients in order to provide a range of services on behalf of the students and families that we serve.
        </p>
        <h3 class="list">Services include:</h3>
        <ul>
          <li>Expert document analysis including reviewing educational services, student medical issues, and progress
            monitoring</li>
          <li>Educational records review</li>
          <li>Instructional observations across educational settings</li>
          <li>Proficient in educational program planning</li>
          <li>Knowledgeable in school practices, school-based interventions, meeting procedures, and parental rights
          </li>
        </ul>
      </div>


    </div>



  </body>

  <!-- <RouterView /> -->
</template>

<style scoped>
header {
  display: block;
  margin-left: auto;
  margin-right: auto;
  /* width: 50%; */
  text-align: center;

  /* line-height: 1.5;
  max-height: 100vh; */
}

address span {
  padding: 10px;
  border-left: 1px solid
}

address span:first-of-type {
  border: 0px;
}

blockquote {
  margin-top: 10px;
  font-size: 20px;
  font-weight: 700;
}

body {
  text-align: center;
}

body div {
  text-align: center;
  padding: 20px 20px 50px 20px;
  border-radius: 20px;
  margin-top: 20px;
}

#about {
  background-color: #dddac2;;
}

#services {
  background-color: #dddac2;;
}

.service {
  background-color:  #a3af8e;
}


.list {
  text-align: left;
}

ul {
  text-align: left;
}

aside {
  padding: 30px 20px 0px 20px;
}


.logo {
 width: 90%;
 padding-top: 20px;
 display: block;
 margin-left: auto;
 margin-right: auto;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: block;
    place-items: center;
    /* padding-right: calc(var(--section-gap) / 2); */
  }

  /* .logo {
    margin: 0 2rem 0 0;
  } */

  header .wrapper {
    display: block;
    /* place-items: flex-start; */
    flex-wrap: wrap;
    place-items: center;
  }

  nav {
    text-align: center;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
}
</style>
