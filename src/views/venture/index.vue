<template>
  <div id="venture">
    <div class="container-fluid">
      <div class="row">
        <div class="col-lg-6 col-lg-offset-3 align-left">
          <h2><strong>Venture.ng</strong></h2>

          <div id='v-head' class="opac-0 m-b-25" :class="{ 'animated fadeInUp': true }">

            <div class="row">
              <div class='col-md-7'>
                <img class="image-size" src="/img/venture/HighExample/Game Board Page High.png" />
              </div>
              <div class='col-md-5'>
                <h3><strong>The Basics</strong></h3>
                <strong>Role</strong>
                <br />
                Researcher, UX Designer and Developer
                <br />
                <br />
                <strong>Tools</strong>
                <br />
                Sketch and Invision
                <br />
                <br />
                <strong>Time Constraint</strong>
                <br />
                3 weeks
              </div>
            </div>

            <h3><strong>The Overview</strong></h3>
            <p>The idea was to create an application for people interested in tabletop to be able to play with friends or family that are
              in different locations. Tabletop is a fun experience and no one should be left out just because they can’t attend an in
              person game session. There are some tools out now that players and game masters use but often times they are pricey or very
              frustrating to use.
            </p>
            <p>I wanted to create an application that is easy to use, easy to access and has all of the information needed for whatever
              ruleset is decided for the game.
            </p>
          </div>

          <div id='v-user' class="opac-0 m-b-25" :class="{ 'animated fadeInUp': scrollY > 795 || isApplied('v-user') }">
            <h3><strong>User Research</strong></h3>
            <p>For my user research, I conducted several in person interviews and put out a survey on a tabletop reddit.</p>
            <p>I found that there are a lot of people already playing virtual tabletop games and are not at all adverse to not having a
              physical tabletop system. However, there are aspects of physical tabletop that players and game masters alike would like to
              have such as physical dice and game ruleset books.
            </p>
            <p>At the same time, there are problems that cross between a physical tabletop game and a virtual tabletop game that cause
              snags during gameplay for everyone. I found that a lot of players have a lot of trouble with calculating numbers on their
              character sheets and during combat. This fact causes game masters distress because it takes forever then for a player to be
              ready and that means lost time during a game. Players, though, are not the only ones with problems. Game masters also have
              to go through alot of steps to get a game ready from prepping maps and tokens to figuring out what they’re going to run for
              a game. With many different places to find information it isn’t easy for players or game masters to be 100% ready for a game.
            </p>
            <p>The main problem comes down to: How can a complex tabletop system be made easy to use for both players and game masters?</p>
          </div>

          <div id='v-1' class="opac-0 m-b-25" :class="{ 'animated fadeInUp': scrollY > 1141 || isApplied('v-1') }">
            <h3><strong>Competetive Analysis</strong></h3>
            <img src="/img/venture/CompetetiveAnalysis.png" id="analysis" />
          </div>
          <div id='v-2' class="opac-0 m-b-25" :class="{ 'animated fadeInUp': scrollY > 1623 || isApplied('v-2') }">
            <h3><strong>Affinity Map</strong></h3>
            <img src="/img/venture/affinitygraph.png" id="affinity" />
          </div>

          <div id='v-3' class="opac-0 m-b-25" :class="{ 'animated fadeInUp': scrollY > 2189 || isApplied('v-3') }">
            <h3><strong>Storyboard</strong></h3>
            <img class="image-size" src="/img/venture/Storyboard.png" />
          </div>

          <div id='v-4' class="opac-0 m-b-25" :class="{ 'animated fadeInUp': scrollY > 2710 || isApplied('v-4') }">
            <h3><strong>Wireframes Start to Finish</strong></h3>
            <img class="image-size" src="/img/venture/HighExample/PaperPrototype3.png" />
            <img class="image-size" src="/img/venture/HighExample/Game Board Page.png" />
            <img class="image-size" src="/img/venture/HighExample/Game Board Page High.png" />
          </div>

          <div id='v-5' class="opac-0 m-b-25" :class="{ 'animated fadeInUp': scrollY > 4894 || isApplied('v-5') }">

            <h3><strong>User Testing</strong></h3>
            <p>The things I thought were great, were not! But that was completely perfect. The feedback was englightening and made me
              rethink a lot of the design choices I had made. Little known fact, I like iterating on my wireframes!
            </p>
            <p>The main feedback: “The widgets on the game board are too small. I don’t feel like I’ll have enough space to see all of the
              important information, especially on the map.”
            </p>
            <p>Normally, a table top game map on a Virtual Table Top system spans the whole screen. It allows the user to pan around the
              map and zoom in and zoom out. My original idea was to ax that as I was going to have other elements that could be positioned
              around the page and I didn’t want the user to feel like everything was overlapping too much. However, table top players like
              their large maps. So I axed my own idea and changed it so that user could resize their map, as long as it wasn’t too small,
              and allow them to collapse and expand other widgets to give them optimal viewing space.
            </p>
            <p>Next important feedback: “The bar at the top of the game board screen isn’t clear that it means a new window will be opened
              up. In that aspect, opening a new window would be the same as putting a bar up top that allows the user to change their
              settings. By the way, why can’t I change my game board settings here?”
            </p>
            <p>This was a very valid point. I had only given the user the option to change their game settings outside of the game board.
              That makes no sense! Each game would have their own settings based on the user’s preference for that game’s play style. Maybe
              in one game the user isn’t using video at all and as such wouldn’t even need the video widget anymore. This also brought to
              light, in pairing with the previous feedback, that the Data Library widget was going to suffer if left on the game board.
              There was going to be too much information to be displayed in a widget. So I changed the idea of new window, gave the user a
              dropdown bar that allows them to open a new window with the data library, change their settings and exit the game board.
              Exiting the game board would return the user to their Games page instead of closing the application completely.
            </p>
          </div>

          <div id='v-6' class="opac-0 m-b-25" :class="{ 'animated fadeInUp': scrollY > 5362 || isApplied('v-6') }">
            <h3><strong>Invision Prototype</strong></h3>
            <a href="https://projects.invisionapp.com/share/4GGQHVG2BK7#/screens/289856614_Home_Page" target="_blank">
            <img src="/img/invisionapp.png" id="invision" />
            </a>
            <h3><strong>Technical Demo</strong></h3>
            <p>The Game Board page of Venture.ng features widgets that can be moved, resized, collpased and expanded so I wanted to show
              just exactly how that would work. Because of that I decided that I would flex my budding developer muscles and put together
              a technical demonstration. I used HTML, CSS and JQuery to put together the demo. Check it out
              <a href="https://jessicawise.github.io/clickablePrototype/" target="_blank">here</a>.
            </p>
          </div>

          <div id='v-final' class="opac-0 m-b-25" :class="{ 'animated fadeInUp': scrollY > 5607 || isApplied('v-final') }">
            <h3><strong>What I Would Add</strong></h3>
            <p>
            <ul>
              <li>Game Master Specific Game Board. Game Masters run the game and create the world and as such they need to have access to different assets than
                players do.
              </li>
              <li>Character Sheet Onboarding.Character sheets are hard and most players aren’t good at traversing a ruleset’s player guides. A guided Character
                Sheet creation would chop off some time when creating a character.
              </li>
              <li>Ruleset Based Data Library. Players are bad at even obtaining player guide books. Not all information for each ruleset is avaliable online either. A centralized Data Library would give players without access to the books, the information they need.</li>
              <li>Friends. Not everyone has friends or habitually checks the looking for group reddit and these people also need a way to
                play tabletop (even with strangers). The idea would be to create a board within the website for GM’s and Players to
                recruit each other for games
              </li>
            </ul>
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
  import TrackScroll from '@/mixins/TrackScroll.vue'
  import ScrollToNav from "@/mixins/ScrollToNav.vue"
  export default {
      name: "venture",
      mixins: [
          ScrollToNav,
          TrackScroll
      ],
      methods: {
      isApplied(id) {
          const el = document.getElementById(id)
          if (!el) return;
          if (el.classList.contains('animated')) {
              return true;
          }
      }
  }
  }
</script>

<style lang="scss">
    #streetsmarts {

        .opac-0 m-b-25 {
            opacity: 0;

            &.animated {
                opacity: 1;
                transition: opacity .5s;
            }
        }
    }
</style>
