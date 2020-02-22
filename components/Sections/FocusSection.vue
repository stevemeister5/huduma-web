<template>
  <section class="section industries_section">
    <h2 class="slideInUp">
      About Us
    </h2>
    <div>
      <h1 style="font-weight: bolder">
        Together we will go far
      </h1>
      <p>
        Any mission to the Moon, the Mars, GEO, LEO, deep Space, or Co-orbiting an Asteroid, we are providing a way of which spacecrafts from different institutions with different missions to share informations with each other at low costs and with small system resources.
      </p>
      <p>
        <strong>Phase One:</strong> we have created ANGANET  a next generation Outer Space based Network enabling data sharing for LEO Satellites, which provides an infrastructure in which satellites from different institutions with different missions to share information with each other at low cost and with small system resources for global real-time coverage, such that anytime anywhere on Earth to be accessible.
        Cheers! ANGANET is the new IoT to the LEO Outer Space.
      </p>
      <p>
        <strong>Current Situation; </strong>To build a full global coverage satellite constellation in LEO alone takes about 10 years and costs about $10 billion (Starlink costs-SpaceX, feb,2018) which proves to be a very expensive for a single institution to handle.
      </p>
      <p>
        <strong>
          Our Solution – ANGANET
        </strong>
        cut costs from $10 billion to $1 million, Which is a 10,000% decrease of price and a reduce of time taken from 10 years of designing, building and deploying to few months of integration with our ready-made infrastructures.
      </p>
      <p>
        Our Mission: facilitating communication and collaboration between those who are bold enough to find purpose in the vast cosmic arena of the universe.
      </p>
      <p>
        Our Vision: Having an intelligent and sustainable Outer Space communication and collaboration Network.
      </p>
      <p>
        We are a Participant Partner with the United Nations Global Compact, the largest United Nations Corporate Sustainability Initiative where we are contributing to mobilizing a global partnership and collaboration in Outer Space Activities as we create the World, we all want. We also work with Astronomy and Space Science Association of Tanzania as our advisory partner to advise and coach us in ethical astronomical practices.
      </p>
      <h1>
        Why Using ANGANET:
      </h1>
      <p>
        1. Always get the data you want: ANGANET is an intelligent network, Thanks to Artificial Intelligence, ANGANET is an intelligent, content-aware network able to identify, process, store, and distribute data.
        <br>
        2. Have a Worldwide Satellite real-time coverage: ANGANET is the only network that can intergrade heterogeneous the existing worldwide satellite systems in space with the network on the ground with immediate data processing, data storage and real-time information sharing which reduces the transmission delay such that anytime anywhere on Earth to be accessible.
        <br>
        3. Have a real-time Global traffic control system. ANGANET helps with debris information awareness communications, hence improves safety and sustainability in space.
        <br>
        4. Budget-friendly options. collaborating with others by using ANGANET reduce costs exponentially unlike individual satellite constellations.
        <br>
        5. facilitate global collaboration. Any organization of any size, any nation from every part of the World can use ANGANET, we complete the experience of a global community
      </p>
      <p>
        <strong>
          Hudumaplus Research Lab.
        </strong> We have a lab to conduct researches and develop prototypes for communications and collaboration for space based commercial and government missions in space. Also researchers will look at the future of our Space in the discovery and use of Space resources for communication and collaboration between institutions and nations in different missions, also how to extend those infrastructures to enable Space settlements, be it in Mars, the Moon, in Low Earth Orbit, or Co-orbiting an asteroid.
      </p>
      <h1>A word from the CEO:</h1>
      <p>
        We are living in a world where civil wars, violence, poverty are common words to hear due to limited resources, in October 1978 my mother (Helena Kabakama) witnessed a deadly Kagera war, she couldn’t go to school although she was ready for it, all she could see was children dying, pregnant women giving birth before its time, thanks to underground bunkers which protected her and other people from falling bombs and other attacks, many died not only from my clan but from all other families too, not to say that until this very minute, other people from different countries around the World are killing each other, all of these are due to limited resources on our planet Earth, in the Outer Space there are unlimited resources in the whole Universe, the observable universe contains around 300 sextillion stars, humans occupy the tiniest fraction of it like a drop in this ocean of space, yet they fight and kill each other over a tiniest fraction of resources. This is why we facilitate communication and collaboration between those who are bold enough to find purpose in that vast cosmic Outer Space, not to forget that we are all wonderers, we want to help finding out what’s there in the vast Universe that we know little about.
      </p>
      <br>
    </div>

    <h2 class="slideInUp">
      Our Team
    </h2>
    <p>
      We don’t believe in the term ‘employees, employer and bosses ‘, we believe in the term ‘dream mates and leaders’, we also believe that we are the engine, and we need more talented people to keep the engine turning, so we need you.
      This mission is too big for any individual person, it is a mission for all of us working together supporting the impacts we see through the Outer Space Economy, joining us is a great chance to do the best for your career, yourself and others, of course the World in general and the future generation.
    </p>
    <div>
      <a-row>
        <a-col
          v-for="(item, index) in team"
          :key="index"
          :xs="24"
          :sm="24"
          :md="12"
          :lg="8"
          :xl="8"
        >
          <team-card
            :image-profile="item.img"
            :description="item.description"
            :username="item.name"
          />
        </a-col>
      </a-row>
    </div>
    <div>
      <h2>
        Corporate Social Responsibilities (CSRs)
      </h2>
      <h4>Our Corporate Social Responsibilities (CSRs) – Sustainable City Project.</h4>
      <p>
        As Part of our Commitment as a Participant Partner of the United Nations Global Compact (UNGC) to advance the ambitions of the Sustainable Development Goals by 2030, We have partnered with XsenseAI Company Limited as our technical partner and we are in cooperation with the Tanzania’s Prime Ministers’ Office ( Investments ) in an initiative called ‘Sustainable City Project’ which is our CSR’s strategic focus to deliver on the 2030 Agenda for Sustainable Development, by helping Tanzania to advance connectivity and efficiency of public services delivery through the use of Artificial Intelligence Technology.
        The urgency to reach the Sustainable Development Goals by 2030 requires every one of us, we are helping government entities of Tanzania to find more innovative approaches for delivering effective, efficient and fair public services. We believe that artificial intelligence (AI) offer new opportunities to reimagine how the public sector can better serve sustainable development needs. Artificial Intelligence has a potential to transform the traditional way of doing things across all government functions and domains hence we are all on this together to help out. Cheers!
      </p>
    </div>
  </section>
</template>

<script>
  import TeamCard from './TeamCard'

  export default {
    components: {
      TeamCard
    },
    data () {
      return {
        team: [
          {
            name: "Cyprian Moses. Chief Executive Officer & Founder",
            img: "https://res.cloudinary.com/intelecs/image/upload/v1582369188/huduma/EEBHc2.jpg",
            description: "Astropreneur and member to UN Space Generation Advisory Council which supports the United Nation on space applications. Winner of the Henry Spurrier Award, awarded in Poland (2018) and the Finalist International Young Achiever Award, Awarded in China (2017)."
          },
          {
            name: "Eng. Goodluck Asenga. Chief Technology Officer & Co-Founder.",
            img: "https://res.cloudinary.com/intelecs/image/upload/v1582369190/huduma/hoYWcn.jpg",
            description: "Leading Hudumanet network development. Majoring in Systems Engineering, focused in Space satellites Communications and Systems Engineering, Expert in M2M Eco systems Sensor Fusion, Machine-to-Machine Intelligence, Time sensitive networking, Cyber physical production systems, M2M Communication multiplication, Performance control, and infrastructure, Cross platform architecture, Traffic models characterization, Addressing, and also indexing."
          },
          {
            name: "Dr Noorali Jiwaji. Astronomer and Chief Advisor",
            img: "https://res.cloudinary.com/intelecs/image/upload/v1582369088/huduma/hk4xEf.jpg",
            description: "Former Member to African Union Space Working Group, Attended the International Astronomical Union School for Young Astronomer at Nsukka, PhD in Environmental Physics, Current International Astronomical Union Liaison for Tanzania, Former Lecturer of the University of Dar Es Salaam, Former Head of ICT and Head of Department of Physical Sciences at the Open University of Tanzania for 16 years combined, Current Chairman of the Astronomy and Space Science Association of Tanzania. "
          },
          {
            name: "January Thomas Magori . Software Engineer",
            img: "https://res.cloudinary.com/intelecs/image/upload/v1582369192/huduma/janu.jpg",
            description: "A graduate in Bachelor of  Computer Engineering,"
          }
        ]
      }
    }
  }
</script>

<style scoped>
  .industries_section {
    background: #f8f8f8;
    overflow: hidden;
    display: block;
    width: 100%;
    box-sizing: border-box;
    height: auto;
  }

  .section {
    padding: 20px 80px 20px 80px;
    /*padding: 50px 10px;*/
    position: relative;
    height: 100%;
    box-sizing: border-box;
    font-size: 18px;
    line-height: 20px;
    color: #333;
    text-shadow: none;
    font-family: "Lato Heavy";
    overflow: hidden;
  }

  .industries_section h2 {
    font-size: 80px;
    color: #e5e5e5;
    display: block;
    margin-block-start: 0.83em;
    margin-block-end: 0.83em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    font-weight: bolder;
  }

  @media only screen and (max-width: 595px) {
    .industries_section h2 {
      font-size: 65px;
    }
  }

  @media only screen and (max-width: 1300px) {
    .industries_section h2 {
      font-size: 60px;
    }
  }

  @media only screen and (max-width: 595px) {
    .industries_section h2 {
      font-size: 45px;
    }
  }

  .product_card:hover {
    box-shadow: 0px 3px 10px 1px #ddd;
    -webkit-transform: translateY(-5px);
    -moz-transform: translateY(-5px);
    -ms-transform: translateY(-5px);
    -o-transform: translateY(-5px);
    transform: translateY(-5px);
  }

  .product_card {
    margin: 20px 3% 20px 0px;
    background: #fff;
    box-shadow: none;
    border: none;
    /*padding: 30px 40px 50px 40px;*/
    box-sizing: border-box;
    -webkit-transition: all 0.8s;
    -moz-transition: all 0.8s;
    -ms-transition: all 0.8s;
    -o-transition: all 0.8s;
    transition: all 0.8s;
    cursor: pointer;
    position: relative;
    display: block;
  }

  .huduma-red-button {
    background: #ef0d33 !important;
    border: none;
    box-shadow: none;
    height: 35px;
    color: #fff;
    border-radius: 3px;
    cursor: pointer;
    font-size: small;
    outline: none;
    background-position: right;
    background-repeat: no-repeat;
  }

  @media only screen and (max-width: 768px) {
    .industries_section p {
      color: #585858;
      line-height: 24px;
    }
  }

  @media only screen and (max-width: 900px) {
    .industries_section p {
      color: #585858;
      line-height: 27px;
    }
  }

  @media only screen and (max-width: 1024px) {
    .industries_section p {
      color: #585858;
      line-height: 18px;
    }
  }

  @media only screen and (max-height: 700px) {
    .industries_section p {
      font-size: 14px;
      line-height: 24px;
    }
  }

  @media only screen and (max-width: 1220px) {
    .industries_section p {
      font-size: 16px;
      line-height: 24px
    }
  }

  @media only screen and (max-width: 1450px) {
    .industries_section p {
      font-size: 14px;
      line-height: 20px;
    }
  }

  .industries_section p {
    color: #585858;
    line-height: 27px;
  }
</style>
