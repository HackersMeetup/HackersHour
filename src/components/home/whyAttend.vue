<template>
  <v-container class="pa-0">
    <v-layout wrap align-center justify-center row fill-height class="my-3">
      <v-flex xs12 md12 lg12 class="pa-2">
        <p class="google-font" style="font-size:150%">Why Attend ?</p>
        <p class="google-font" style="font-size:110%">
          We are creating a platform for the cyber security researchers as well
          as security enthusiast people who really interested to learn something
          new and take exposure of latest trends and issues in cyber security
          and deep dive into cyber security domain. Participating in this event
          will Improve your Pentesting skills, add value to you quantitative and
          qualitative cybersecurity skills, cultivate critical thinking, You
          will understand vulnerabilities in depth, you can Hack All the things
          you want as well as to grow your network and teamwork abilities and Win Prize up to Rs.50000/-
        </p>
        <!-- <v-btn :href="chapterDetails.ChapterMeetupLink" target="_blank" outline color="white" class="ma-0 google-font" style="border-radius:5px;text-transform: capitalize;">Meetup Page</v-btn> -->
        &nbsp;
        
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
import ChapterDetails from "@/assets/data/chapterDetails.json";
export default {
  data() {
    return {
      chapterDetails: ChapterDetails,
    };
  },
};
</script>
