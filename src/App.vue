<script setup>
// import { RouterLink } from 'vue-router'
// import {  RouterView } from 'vue-router'
// import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <img alt="Summit Sprouts Therapy" class="logo" src="@/assets/images/sst-border.png" />

    <div class="wrapper">
      <address>
        <span>Summit County, Colorado</span>
        <span>(719) 838-3915</span>
        <span>erin.stark&#8203;@summitsproutstherapy.com</span>
      </address>
      <blockquote>
        “How we spend our days is, of course, how we spend our lives.” <br /> — Annie Dillard, The Writing Life
      </blockquote>
      <nav>
        <!-- <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink> -->
        <!-- <RouterLink to="{ path: '/#advocacy'}"> Advocacy </RouterLink> -->
        <a href="#about">About Me</a>
        <a href="#occupational-therapy">Occupational Therapy</a>
        <a href="#consulting">Consulting</a>
        <a href="#advocacy">Advocacy</a>
        <a href="#pricing">Pricing</a>
        <a href="/ot-referral-form.pdf" target="_blank">Referral Form</a>
      </nav>
    </div>
  </header>

  <body>
    <div id="about">
      <h1>About Me</h1>
      <p>
        In my 15 years as an occupational therapist, I have worked with infants to seniors in a range of settings, from early intervention to schools, home health to hospitals and skilled nursing facilities. My clients arrive with a range of diagnoses, and together we find the best solutions to meet their needs for daily living. My career and calling is to help you meet your goals. I would love to learn more about you and/or your family. I offer a free 20 minute consultation to help determine your specific needs.
      </p>
      <div id="diagnosis">
        <h3>Examples of Diagnosis</h3>
        <div id="diagnosis-list">
          <ul class="diagnosis">
            <li>ADHD</li>
            <li>Sensory Processing Disorder</li>
            <li>Autism</li>
            <li>Down Syndrome</li>
            <li>Prader Willi's</li>
            <li>Cerebral Palsy</li>
            <li>Developmental Delay</li>
          </ul>
          <ul class="diagnosis">
            <li>Avoidant/Restrictive Food Intake</li>
            <li>Dementia</li>
            <li>Stroke</li>
            <li>Cardiac Issues</li>
            <li>Orthopedic Injury</li>
            <li>Aging in Place</li>
          </ul>
        </div>
      </div>
    <div class="personal">
      <img alt="profile-picture" class="picture" src="@/assets/images/profile-picture.jpg" height="200" />
      <h3><b>Erin Stark OTR/L</b></h3>
      <br>
      <p><u>Education</u></p>
      <p>M.S. Occupational Therapy; Columbia University, NY</p>
      <p>M.Ed. Education Administration; Lamar University, TX</p>
      <p>B.S. Psychology; Denison University, OH</p>
      <br>
      <p><u>Credentials</u></p>
      <p>Department of Regulatory Agencies OT License</p>
      <p>National Board of Occupational Therapy Registration</p>
      <p>Certified Autism Spectrum Disorder Clinical Specialist (ASDCS)</p>
      <p>Pending: ADHD-Certified Rehabilitation Services Provider (ADHD-RSP)</p>

    </div>


  </div>

    <div></div>

    <div id="services">
      <h1>Services</h1>

      <div id="occupation-therapy" class="service">
        <h2>Occupational Therapy</h2>
        <p>
          The goal of occupational therapy is to make sure you can function independently in your daily life at any age. I can help you develop or recover necessary skills, including motor, cognitive, social emotional, organizational, or sensory processing skills.  My goal in providing occupational therapy services is to help you meet your goals.  I am now excited to offer mobile outpatient and virtual therapy services.
        </p>
      </div>

      <div id="consulting" class="service">
        <h2> Community Consulting </h2>
        <p>
          For various community centers there is nothing more important than ensuring the children or adults we care for are able to access the environment safely and ensure their needs are met. I provide trainings and planning support focusing on sensory processing, self regulation, motor skills, and universal design. 
        </p>
        <h3 class="list">Services include:</h3>
        <ul>
          <li>Location designed specific trainings based on initial consultation</li>
          <li>Instructional observations offered in various time increments</li>
          <li>1:1, small group and full staff trainings</li>
          <li>Ongoing in class or group support</li>
          <li>Support with universal design planning</li>
        </ul>
      </div>

      <div id="advocacy" class="service">
        <h2>Advocacy</h2>
        <p>
          As a parent, you want the best for your child. Navigating school system supports, like an IEP or 504, is daunting. I also know how important it is to ensure you have clear communication and a positive relationship with your child's school. My work in schools for the last 13 years paired with my M.Ed. in Education Administration means I am well versed in the school services and regulations to help support your family.
        </p>
        <h3 class="list">Services include:</h3>
        <ul>
          <li>Expert document analysis including reviewing educational services, student medical issues, and progress
            monitoring</li>
          <li>Educational records review</li>
          <li>Instructional observations</li>
          <li>Educational program planning</li>
          <li>Advice regarding school-based interventions, goal writing, meeting procedures, and parental rights</li>
          <li>Attending meetings with the school</li>
        </ul>
      </div>

      <div id="pricing" class="service">
        <h2>Pricing</h2>
        <p>$120 an hour</p>
        <p>Sliding Scale Available</p>
        <p>Discount Packages Available</p>
        <br>
        <p><u>Insurance Options for OT Services</u></p>
        <p><b>Medicaid Accepted</b></p>
        <p>Pending: CHP+, Blue Cross/ Blue Shield, Cigna, Aetna, United</p>
      
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

/* address span {
  padding: 10px;
  border-left: 1px solid
}

address span:first-of-type {
  border: 0px;
} */

b {
  font-weight: 900;
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

div#diagnosis {
  padding: 0;
  /* display:table; */
  h3 {
    padding-bottom: 5px;
  }
  #diagnosis-list{
    padding: 0;
    display: table;
    margin: 0 auto;
    width: auto; 

  }


}

ul.diagnosis {
  /* padding-top: 10px; */
  display: inline-block;
  margin-left: auto;
  margin-right: auto;
  position: relative;
  vertical-align: top;
  max-width: 280px;
  width: auto;
  word-break:normal;
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
  margin-top: 1rem;
  color: #024702;
}

nav a.router-link-exact-active {
  color: #024702;
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
  color: #024702;
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 801px) {
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

  address span {
  padding: 10px;
  border-left: 1px solid
}

address span:first-of-type {
  border: 0px;
}
}


@media (max-width: 800px) {

  address span {
    display: block;
    padding: 3px 0;
  }
  
  nav a {
    display: block;
    border: 0px;
    padding: 5px 0;
  }

}
</style>
