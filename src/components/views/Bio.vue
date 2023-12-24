<template>
  <div>
    <img class="self" src="@/assets/Biography/seanAndTaylor.png" />
    <h2 class="header">Sean and Taylor</h2>
    <h4 class="subtitle" style="padding-bottom: 10px">
      Age: 30 | Height: 6'1" | Occuptation: Wealth Management |
      Hobbies: ...
    </h4>
    <h4 class="" style="text-align: left;">St. Louis 📍</h4>
    <div class="badge-grid">
      <div style="background-color: #ff5733; padding: 10px;">
        Leo
      </div>
    </div>
    <!-- <div class="badge-grid">
      <img
        class="badge"
        alt="Swift"
        src="https://img.shields.io/badge/-Swift-orange"
      />
      <img
        class="badge"
        alt="Python"
        src="https://img.shields.io/badge/-Python-blue"
      />
      <img
        class="badge"
        alt="JavaScript"
        src="https://img.shields.io/badge/-Javascript-yellow"
      />
      <img
        class="badge"
        alt="SQL"
        src="https://img.shields.io/badge/-SQL-lightgrey"
      />
      <img
        class="badge"
        alt="Git"
        src="https://img.shields.io/badge/-Git-critical"
      />
      <img
        class="badge"
        alt="HTML/CSS"
        src="https://img.shields.io/badge/-HTML%2FCSS-yellowgreen"
      />
      <img
        class="badge"
        alt="SwiftUI"
        src="https://img.shields.io/badge/-SwiftUI-3e8bc3"
      />
      <img
        class="badge"
        alt="Vue"
        src="https://img.shields.io/badge/-VueJS-61b083"
      />
      <img
        class="badge"
        alt="Flask"
        src="https://img.shields.io/badge/-Flask-406893"
      />
      <img
        class="badge"
        alt="MongoDB"
        src="https://img.shields.io/badge/-MongoDB-4ca158"
      />
      <img
        class="badge"
        alt="SQLite"
        src="https://img.shields.io/badge/-SQLite-64a2c9"
      />
      <img
        class="badge"
        alt="Figma"
        src="https://img.shields.io/badge/-Figma-8c5aee"
      />
    </div> -->
    <div class="inner-content">
      <h3 class="heading"><b>Welcome</b></h3>
      <p class="paragraph">
        Welcome to our dating site. We are Sean and Taylor and we’ve been friends for 15 years. 
        <br><br>
        We live in St Louis Missouri, and are looking for dates. We are sick of the dating app scene and are so happy that you found us here! 
        <br><br>
        Please take a look around, learn a little bit about us, and if you like what you see, send us an email. 
      </p>
    </div>
    <div class="inner-content">
      <h3 class="heading"><b>About</b></h3>
      <p class="paragraph">
        We grew up in St Louis County, Missouri, with good liberal-Catholic values and hard-working Midwestern ideals. We come from good local families that value being involved and giving back to our local community. 
        <br><br>
        We graduated in 2012 from local parochial schools and went on to higher education together.
        <br><br>
        Together we enjoy St. Louis’ notable food scene, hanging and drinking a few brews or spicy margs, and watching documentaries. 
        <br><br>
        Our favorite memory is probably sharing a hotel room this past summer at our mutual friend’s wedding. 
        <br><br>
        We look forward to finding our one true love and raising a family in St Louis.
      </p>
      
    </div>

    <div class="inner-content">
      <h3 class="heading"><b>Testimonials</b></h3>
      <p class="paragraph">
        “Funny, gentle, compassionate…” - Anonymous 
        <br><br>
        “…talked non stop but I definitely laughed a couple of times, no awkward pauses” - Cheryl W.
        <br><br>
        “Two of the most responsible, helpful people I’ve ever met.” - Mike B.
        <br><br>
        “Good hang” - Justin R.
        <br><br>
        “Reliable, dependable” - Mike S.
        <br><br>
        “Loving, other-oriented” - Maggie T. 
        <br><br>
        “Still one of the best cuddles I’ve ever had on a basement floor.” - Noah F. 
        <br><br>
        “These two are awesome.” - Mike F.
        <br><br>
        4/5 previous partners reported feeling at least moderately satisfied
      </p>
    </div>

    <div class="inner-content">
      <h3 class="heading"><b>FAQ</b></h3>
      <p style=""><i>Are we looking for a third?</i></p>
      <p class="paragraph">
        No! Why do people keep asking us this? We are just two friends, looking for a deeper connection and whatever life has to offer us. 
      </p>
      <p style=""><i>Could please address the hotel room situation?</i></p>
      <p class="paragraph">
        What is there to address? We shared a hotel room, nothing more. It was just a couple of friends, sharing a hotel room. Another friend of ours was going to join, but bailed at the last second, so it was just the two of us. It was really nice. 
      </p>
    </div>

  </div>

</template>

<style scoped>
.badge-grid {
  display: table;
  align-items: center;
  margin-top: 20px;
}

.badge {
  width: auto;
  height: 20px;
  border-radius: 0px;
  font-size: 12px;
  padding-right: 10px;
  /* box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.12), 0 6px 20px 0 rgba(0, 0, 0, 0.1); */
}

.self {
  width: 100%;
  height: auto;
  /* border-radius: 5px; */
}

.subtitle {
  font-size: 12px;
  color: gray;
}

.heading {
  padding-bottom: 5px;
}

.header {
  padding-top: 20px;
  padding-bottom: 20px;
}

.inner-content {
  padding-top: 30px;
}

h2,
h4,
h3 {
  padding: 0;
  margin: 0;
}
</style>
