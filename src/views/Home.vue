<template>
  <div class="container my-5">
    <Posts :posts="posts"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Posts from '../components/Posts'

export default {
  name: 'Home',
  components: {
    Posts

  },
  data(){
    return{
      posts:[
            {
          id: 1,
          text: 'Doctors Appointment',
          body: 'Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry\'s standard dummy text ever since the 1500s, when an',
          tags:['programming','js']
        },
        {
          id: 2,
          text: "Meeting at School",
          body: "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the ",
          tags:['vuejs','reactjs']

        },
        {
          id: 3,
          text: "Food Shopping",
          body: "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an",
          tags:['vuejs','anjularjs']
        }
      ]
    }
  },
  methods:{

  },

}
</script>
