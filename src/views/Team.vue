<template>
  <v-content class="pa-0">

    <v-container fluid class="mt-3 mb-0">
      <v-layout wrap align-center justify-center row fill-height class="my-0">
        <v-flex xs12 md10 class="my-0">
            <p class="google-font mb-0" style="font-size:200%;color:#616161">Our lineup of big thinkers and even bigger doers</p>
            <p class="google-font mt-0 mb-0" style="font-size:110%">The Hackers Meetup is known to all around the world. Everyone is Attending 'meetups and workshops', Participating in 'Events', Reading 'Blogs', Doing 'Reasearch' and Getting 'jobs'. For community members, they are things that just works, but not for us. Our Team see much more: Skill Gap, Latest Trends, security issues, complex technology stacks. And that is what THM is about. </p>

            <p class="google-font mt-3 mb-0" style="font-size:110%">Our goal is to Creating Cyber Security Researchers for global workforce and bridge the gap with Industry And Our Core Team is: </p>

        </v-flex>
      </v-layout>
    </v-container>

    <v-container fluid >
      <v-layout wrap align-center justify-center row fill-height>
        <v-flex xs12 md10 class="">
          <coreTeam/>
        </v-flex>
      </v-layout>
    </v-container>

    <v-container fluid >
      <v-layout wrap align-center justify-center row fill-height>
        <v-flex xs12 md10 class="">
          <organizingTeam/>
        </v-flex>
      </v-layout>
    </v-container>

   


  </v-content>
  
</template>

<script>
import TeamDetails from '@/assets/data/chapterDetails.json'
import coreTeam from '@/components/team/coreTeam'
import organizingTeam from '@/components/team/organizingTeam'
  export default {
    components: {
      coreTeam,
      organizingTeam
    },
    data() {
      return {
        TeamDetails: TeamDetails,
      }
    },
  }
</script>
