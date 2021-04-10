<template>
  <div class="main">
    <div class="top-container">
      <img class="tc-first-image" src="../assets/images/cc1.png" alt="candan-img">
    </div>

    <div class="middle-container">
      <div id="mySidenav" class="sidenav">
        <a href="#hrf-intro" id="about">About</a>
        <a href="#hrf-experience" id="myExperience">Experience</a>
        <a href="#hrf-education" id="myEducation">Education</a>
        <a href="#hrf-skills" id="mySkills">Skills</a>
        <a href="#hrf-contact" id="contact">Contact</a>
      </div>

      <div id="hrf-intro" class="profile">
        <img class="img-personal" src="../assets/images/cc.png" alt="personal image">
        <h2>About.</h2>
        <p class="intro">I am a software developer who focuses on Java, C/C++, Python languages. Currently I
          am studying for a master degree at Galatasaray University as an Computer Engineering.
          Previously I studied bachelor degree in Electrical-Electronics Engineering at Anadolu
          University. During my bachelor's I attended two Erasmus exchange programs and I
          attended two international competitions.</p>
        <p class="intro">
          Personally I am interested in travelling and world cuisine . In my free time I am always
          trying to travel inside or outside of the country. </p>
      </div>
      <hr>
      <div id="hrf-experience" class="experience">
        <h2 style="margin-bottom: 3%">Experience.</h2>
        <div class="experience row">
          <div class="col-6">
            <h4>Softtech</h4>
            <p class="experience-period">
              August 2020 -
              Present
            </p>
          </div>
          <div class="job-detail col-5">
            <h4>Software Developer</h4>
            <ul class="list-group">
              <li>Responsible for backend projects with Java(Spring, Spring boot, Hibernate, POJO Java 7,8).</li>
              <li>Responsible for frontend projects with VueJs.</li>
              <li>Writing Services on WAS IBM server.</li>
              <li>Responsible for developing algorithms which interact with databases(Oracle, db2, postgresql etc).</li>
            </ul>
            <span class="experience-details">
					<span class="location">
            <a href="https://www.google.com/maps/place/Softtech+Tuzla+%C5%9Eube/@40.841319,29.3067783,17z/data=!3m1!4b1!4m5!3m4!1s0x14cadc3be723f5ab:0x626667631b58009a!8m2!3d40.841319!4d29.308967">
                    <font-awesome-icon :icon="['fas', 'map-marker-alt']" size="1x"/>
						Online
            </a>
            <a>|</a>
            <a href="https://softtech.com.tr/en/homepage/">
              <font-awesome-icon :icon="['fas', 'laptop']" size="1x"/> Softtech</a>
          </span>
				</span>

          </div>
        </div>
        <div class="experience row">
          <div class="col-6">
            <h4>Ericsson</h4>
            <p class="experience-period">
              March 2019 -
              August 2020
            </p>
          </div>
          <div class="job-detail col-5">
            <h4>Software Developer</h4>
            <ul class="list-group">
              <li>Responsible for embedded software programs on Java/C++.</li>
              <li>Writing Services on Linux(RedHat) operating systems.</li>
              <li>Responsible for developing algorithms which interact with databases(Oracle, mySQL, etc.) and
                cashing(Redis) systems.
              </li>
            </ul>
            <a href="https://www.ericsson.com/en">
              <font-awesome-icon :icon="['fas', 'laptop']" size="1x"/>
              Ericsson</a>
          </div>
        </div>
        <div class="experience row">
          <div class="col-6">
            <h4>Opthema Technology</h4>
            <p class="experience-period">
              March 2018 -
              March 2019
            </p>
          </div>
          <div class="job-detail col-5">
            <h4>Software Developer</h4>
            <ul class="list-group">
              <li>Responsible for embedded programs C/C++.</li>
              <li>Responsible for IOT projects(research, hardware designing,software programming).</li>
              <li>Responsible for test programs on Python for embedded interaction programs.</li>
              <li>Dealing with foreign customers of department ( negotiation of IOT department businesses).</li>
            </ul>
            <a href="https://opthemateknoloji.com/">
              <font-awesome-icon :icon="['fas', 'laptop']" size="1x"/>
              Opthema</a>
          </div>
        </div>
        <div class="experience row">
          <div class="col-6">
            <h4>Master Decos Electronics</h4>
            <p class="experience-period">
              December 2015 -
              March 2018
            </p>
          </div>
          <div class="job-detail col-5">
            <h4>Embedded Systems Engineer</h4>
            <ul class="list-group">
              <li>Designing PCB boards with Altium Designer.</li>
              <li>Testing hardware designs, re-calibrating the designs according to test.</li>
              <li>Writing codes for Arm cortex-STM32xxx microcontroller with C/C++ languages.</li>
              <li>Creating graphical user interface for calibrating and testing embedded designs with C# language.</li>
              <li>Using serial communications RS232/485, Ethernet ,Modbus,USB etc...</li>
              <li>Working with single board computers (Latte Panda, UDOO, Beagle bone etc..) in Linux/Windows
                environment
              </li>
            </ul>
            <a href="http://masterdecos.com/">
              <font-awesome-icon :icon="['fas', 'laptop']" size="1x"/>
              Decos</a>
          </div>
        </div>
      </div>
      <hr>
      <div id="hrf-education" class="education">
        <h2 style="margin-bottom: 3%">Education.</h2>
        <div class="education row">
          <div class="col-6">
            <h4>Galatasaray University</h4>
            <p class="experience-period">
              September 2018 -
              Present
            </p>
          </div>
          <div class="job-detail col-5">
            <h4>Computer Engineering MS</h4>
            <ul class="list-group">
              <li>Currently I am on my thesis stage. My degree will be finished at 2021 spring semester.</li>
            </ul>
            <span class="education-details">
					<span class="location">
            <a href="https://www.gsu.edu.tr/">
              <font-awesome-icon :icon="['fas', 'graduation-cap']" size="1x"/> Galatasaray</a>
          </span>
				</span>
          </div>
        </div>
        <div class="education row">
          <div class="col-6">
            <h4>Anadolu University</h4>
            <p class="experience-period">
              March 2019 -
              August 2020
            </p>
          </div>
          <div class="job-detail col-5">
            <h4>Electrical/Electronics
              Engineering</h4>
            <ul class="list-group">
              <li>In this university my lectures were %100 English.</li>
              <li>During my bachelor years I made 2 Erasmus exchange program(Sweden, Belgium).</li>
              <li>During my bachelor years I attend 2 international student competition (UK euroelectric students
                awards/2014, USA-Student Unmanned Arial Systems/SUAS/2015) .
              </li>
            </ul>
            <a href="https://www.anadolu.edu.tr/en">
              <font-awesome-icon :icon="['fas', 'graduation-cap']" size="1x"/>
              Anadolu</a>
          </div>
        </div>
      </diV>
      <hr>
      <div id="hrf-skills" class="skills">
        <h2>Skills.</h2>
        <div class="programming skill-row">
          <iframe class="frame-coding" src="https://giphy.com/embed/ZVik7pBtu9dNS" width="480" height="268"
                  frameBorder="0"></iframe>
          <h3>Programming Languages</h3>
          <div>
            <ul class="ulStarRating col-6">
              <li class="liStarRating"><strong>Java
                <star-rating :rating="4" :read-only="true" :star-size="13" :inline="true"
                             :show-rating="false"></star-rating>
              </strong></li>
              <li class="liStarRating"><strong>C/C++
                <star-rating :rating="4" :read-only="true" :star-size="13" :inline="true"
                             :show-rating="false"></star-rating>
              </strong></li>
            </ul>
            <ul class="ulStarRating col-5">
              <li class="liStarRating"><strong>VueJs
                <star-rating :rating="3" :read-only="true" :star-size="13" :inline="true"
                             :show-rating="false"></star-rating>
              </strong></li>
              <li class="liStarRating"><strong>Python
                <star-rating :rating="3" :read-only="true" :star-size="13" :inline="true"
                             :show-rating="false"></star-rating>
              </strong></li>
            </ul>
          </div>

        </div>

        <div class="environment skill-row">
          <img class="img-version" src="../assets/images/version.png" alt="version-img">
          <h3>Environments/Known technologies</h3>
          <div>
            <ul class="ulStarRating col-6">
              <li class="liStarRating">
                <strong>Oracle
                  <star-rating :rating="3.5" :read-only="true" :star-size="13" :increment="0.5" :inline="true"
                               :show-rating="false"></star-rating>
                </strong>
              </li>
              <li class="liStarRating">
                <strong>DB2
                  <star-rating :rating="3.5" :read-only="true" :star-size="13" :increment="0.5" :inline="true"
                               :show-rating="false"></star-rating>
                </strong>
              </li>
              <li class="liStarRating">
                <strong>Postgre
                  <star-rating :rating="3.5" :read-only="true" :star-size="13" :increment="0.5" :inline="true"
                               :show-rating="false"></star-rating>
                </strong>
              </li>
              <li class="liStarRating">
                <strong>IBM-WAS
                  <star-rating :rating="2.5" :read-only="true" :star-size="13" :increment="0.5" :inline="true"
                               :show-rating="false"></star-rating>
                </strong>
              </li>
              <li class="liStarRating">
                <strong>XL-Release
                  <star-rating :rating="2.5" :read-only="true" :star-size="13" :increment="0.5" :inline="true"
                               :show-rating="false"></star-rating>
                </strong>
              </li>
            </ul>

            <ul class="ulStarRating col-6">
              <li class="liStarRating">
                <strong>Git/Bash
                  <star-rating :rating="4" :read-only="true" :star-size="13" :increment="0.5" :inline="true"
                               :show-rating="false"></star-rating>
                </strong>
              </li>
              <li class="liStarRating">
                <strong>SVN
                  <star-rating :rating="4" :read-only="true" :star-size="13" :increment="0.5" :inline="true"
                               :show-rating="false"></star-rating>
                </strong>
              </li>
              <li class="liStarRating">
                <strong>Jira
                  <star-rating :rating="4" :read-only="true" :star-size="13" :increment="0.5" :inline="true"
                               :show-rating="false"></star-rating>
                </strong>
              </li>
              <li class="liStarRating">
                <strong>Linux
                  <star-rating :rating="4" :read-only="true" :star-size="13" :increment="0.5" :inline="true"
                               :show-rating="false"></star-rating>
                </strong>
              </li>

              <li class="liStarRating">
                <strong>Splunk
                  <star-rating :rating="2.5" :read-only="true" :star-size="13" :increment="0.5" :inline="true"
                               :show-rating="false"></star-rating>
                </strong>
              </li>
            </ul>

          </div>

        </div>
        <div class="hardware skill-row">
          <img class="img-iot" src="../assets/images/pcb1.png" alt="iot-img">
          <h3>Hardware Designing</h3>
          <div>
            <ul class="ulStarRating col-6">
              <li class="liStarRating">
                <strong>Altium Designer
                  <star-rating :rating="4" :read-only="true" :star-size="13" :increment="0.5" :inline="true"
                               :show-rating="false"></star-rating>
                </strong>
              </li>
              <li class="liStarRating">
                <strong>MCU
                  <star-rating :rating="4" :read-only="true" :star-size="13" :increment="0.5" :inline="true"
                               :show-rating="false"></star-rating>
                </strong>
              </li>
              <li class="liStarRating">
                <strong>IOT
                  <star-rating :rating="4" :read-only="true" :star-size="13" :increment="0.5" :inline="true"
                               :show-rating="false"></star-rating>
                </strong>
              </li>
            </ul>
            <ul class="ulStarRating col-6">
              <li class="liStarRating">
                <strong>RF Design
                  <star-rating :rating="3" :read-only="true" :star-size="13" :increment="0.5" :inline="true"
                               :show-rating="false"></star-rating>
                </strong>
              </li>
              <li class="liStarRating">
                <strong>Eagle CAD
                  <star-rating :rating="2" :read-only="true" :star-size="13" :increment="0.5" :inline="true"
                               :show-rating="false"></star-rating>
                </strong>
              </li>
              <li class="liStarRating">
                <strong>Serial Comm.
                  <star-rating :rating="4" :read-only="true" :star-size="13" :increment="0.5" :inline="true"
                               :show-rating="false"></star-rating>
                </strong>
              </li>
            </ul>
          </div>


        </div>
      </div>
      <hr>
      <div id="hrf-contact" class="contact-me">
        <h2>Get In Touch</h2>
        <h3>Please send me your message</h3>
        <b-button v-b-modal.modal-prevent-closing>CONTACT ME</b-button>
        <b-modal
            id="modal-prevent-closing"
            ref="modal"
            title="Please write message for Cagri CANDAN"
            @show="resetModal"
            @hidden="resetModal"
            @ok="handleOk">
          <form ref="form" @submit.stop.prevent="handleSubmit">
            <b-form-group
                label="Message"
                label-for="name-input"
                invalid-feedback="Name is required"
                :state="nameState"
            >
              <b-textarea
                  id="name-input"
                  v-model="message"
                  :state="nameState"
                  required>
              </b-textarea>
            </b-form-group>
          </form>
        </b-modal>
        <b-alert
            :show="dismissCountDown"
            dismissible
            variant="warning"
            @dismissed="dismissCountDown=0"
            @dismiss-count-down="countDownChanged"
        >
          <p>Sending data {{ dismissCountDown }} seconds...</p>
          <b-progress
              variant="success"
              :max="dismissSecs"
              :value="dismissCountDown"
              height="4px"
          ></b-progress>
        </b-alert>
      </div>
    </div>
    <div class="bottom-container">
      <h3>Please check on my accounts</h3>
      <a class="footer-link" href="https://tr.linkedin.com/in/cagricandan/">
        <font-awesome-icon :icon="['fab', 'linkedin']" size="3x"/>
      </a>
      <a class="footer-link" href="https://twitter.com/cagricandan91/">
        <font-awesome-icon :icon="['fab', 'twitter']" size="3x"/>
      </a>
      <a class="footer-link" href="https://tr-tr.facebook.com/cagri.candan">
        <font-awesome-icon :icon="['fab', 'facebook']" size="3x"/>
      </a>
      <a class="footer-link" href="https://github.com/Candan26/">
        <font-awesome-icon :icon="['fab', 'github']" size="3x"/>
      </a>
      <p></p>
      <p>© 2021 Cagri Candan</p>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    'disabled': Boolean
  },
  name: "Candan",
  data() {
    return {
      dismissSecs: 3,
      dismissCountDown: 0,
      showDismissibleAlert: false,
      message: '',
      nameState: null
    }
  },
  methods: {
    countDownChanged(dismissCountDown) {
      this.dismissCountDown = dismissCountDown
    },
    showAlert() {
      this.dismissCountDown = this.dismissSecs
    },
    checkFormValidity() {
      const valid = this.$refs.form.checkValidity()
      this.nameState = valid
      return valid
    },
    resetModal() {
      this.message = ''
      this.nameState = null
    },
    handleOk(bvModalEvt) {
      // Prevent modal from closing
      bvModalEvt.preventDefault()
      // Trigger submit handler
      this.handleSubmit()
    },
    handleSubmit() {
      if (!this.checkFormValidity()) {
        return
      }
      const requestOptions = {
        method: "POST"
      };
      fetch('http://165.22.200.210:7547/api/website/addMessage/?name=candan&message=' + this.message, requestOptions);
      this.showAlert();
      // Hide the modal manually
      this.$nextTick(() => {
        this.$bvModal.hide('modal-prevent-closing')
      })
    }
  }
}
</script>

<style scoped>
body {
  margin: 0;
  color: #40514E;
  text-align: center;
  font-family: 'Merriweather', serif;
}

h1 {
  font-size: 5.625rem;
  margin: 50px auto 0 auto;
  line-height: 2;
  font-family: 'Permanent Marker', sans-serif;
}

h2 {
  color: #66BFBF;
  font-family: 'Montserrat', sans-serif;
  font-size: 2.5rem;
  font-weight: normal;
  padding-bottom: 10px;
}

h3 {
  color: #11999E;
  font-family: 'Montserrat', sans-serif;
  font-size: 1.5rem;
  font-weight: normal;
}

p {
  line-height: 2;
}

hr {
  border: dotted #EAF6F6 6px;
  border-bottom: none;
  width: 30%;
  margin: 50px auto;
}

a {
  color: #11999E;
  font-family: 'Montserrat', sans-serif;
  margin: 10px 20px;
  text-decoration: none;
}

a:hover {
  color: #AAAA;
}

/**STYLE CLASSES **/
/* Containers */
.top-container {
  background-color: #9ad3bc;
  position: relative;
  padding-top: 2%;
}

.middle-container {
  margin: 10% 0;
}

.bottom-container {
  background-color: #9ad3bc;
  margin-top: 1%;
  padding: 2% 0 2%;
}

.skill-row {
  width: 30%;
  margin: 2% auto 1% auto;
  text-align: left;
}


.intro {
  width: 50%;
  margin: auto;
  line-height: 2.0;
  text-align: justify;

}

.experience {
  margin-bottom: 2%;
}

.education {
  margin-bottom: 2%;
}

.job-detail {
  text-align: left;
}

/***********   IMAGES  ************/
.tc-first-image {
  padding-bottom: 2%;
}

.img-personal {
  padding: 1em 1em;
  width: 400px;
}

.img-iot {
  width: 70%;
  border-radius: 30%;
}

.img-iot:hover {
  background-color: red;
}

.img-version {

  width: 70%;
  margin-bottom: 2%;
}

.img-version:hover {
  background-color: gold;
}

.programming {

  align-items: center
}

.environment {

}

.hardware {
  /*margin-right: 10%;*/
}

.btn {
  background: #11cdd4;
  background-image: -webkit-linear-gradient(top, #11cdd4, #11999e);
  background-image: -moz-linear-gradient(top, #11cdd4, #11999e);
  background-image: -ms-linear-gradient(top, #11cdd4, #11999e);
  background-image: -o-linear-gradient(top, #11cdd4, #11999e);
  background-image: linear-gradient(to bottom, #11cdd4, #11999e);

  border-radius: 8px;
  font-family: 'Montserrat', sans-serif;
  color: #ffffff;
  font-size: 20px;
  padding: 10px 20px 10px 20px;
  text-decoration: none;
}

.btn:hover {
  background: #30e3cb;
  background-image: -webkit-linear-gradient(top, #30e3cb, #2bc4ad);
  background-image: -moz-linear-gradient(top, #30e3cb, #2bc4ad);
  background-image: -ms-linear-gradient(top, #30e3cb, #2bc4ad);
  background-image: -o-linear-gradient(top, #30e3cb, #2bc4ad);
  background-image: linear-gradient(to bottom, #30e3cb, #2bc4ad);
  text-decoration: none;
}

/***********   FRAMES  ************/
.frame-coding {
  pointer-events: none;
  width: 95%;

}

#mySidenav a {
  position: fixed;
  right: -121px;
  transition: 0.5s;
  padding: 10px;
  width: 120px;
  text-decoration: none;
  font-size: 15px;
  color: white;
  border-radius: 0 5px 5px 0;
}

#mySidenav a:hover {
  right: -20px;
}

#about {
  top: 20px;
  background-color: #4CAF50;
}

#myExperience {
  top: 65px;
  background-color: #2196F3;
}

#myEducation {
  top: 110px;
  background-color: #f44336;
}

#mySkills {
  top: 155px;
  background-color: #555
}

#contact {
  top: 200px;
  background-color: #28527a
}


/*Star Raiting*/
.liStarRating {
  list-style: none;
}

.ulStarRating {
  display: inline-block;
  vertical-align: top;
  padding-left: 0;

}


/* small size screens */

@media (max-width: 700px) {

  p {
    font-size: 15px;
  }

  li {
    font-size: 15px;
  }

  .frame-coding {
    pointer-events: none;
    width: 95%;
    margin-bottom: -70px;
    margin-top: -100px;
  }

  h1 {
    font-size: 5.625rem;
    margin: 50px auto 0 auto;
    line-height: 2;
    font-family: 'Permanent Marker', sans-serif;
  }

  h2 {
    color: #66BFBF;
    font-family: 'Montserrat', sans-serif;
    font-size: 2rem;
    font-weight: normal;

  }

  h3 {
    color: #11999E;
    font-family: 'Montserrat', sans-serif;
    font-size: 1.5rem;
    font-weight: normal;
  }

  p {
    line-height: 1;
  }

  hr {
    border: dotted #EAF6F6 6px;
    border-bottom: none;
    width: 30%;
    margin: 10px auto;
  }

  #about, #myExperience, #myEducation, #mySkills, #contact {
    display: none;

  }
}
</style>