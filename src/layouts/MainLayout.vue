<template>
  <q-layout view="lHh Lpr lFf">
    <!-- 
    <q-drawer
      v-model="leftDrawerOpen"
      show-if-above
      bordered
      dark
      class="bg-primary scrollbar text-white"
      >
      <q-list>
        <q-item-label
          header
          class="text-grey-8"
        >
          Essential Links
        </q-item-label>
        <EssentialLink
        />
      </q-list>
    </q-drawer> -->

    <q-page-container>
      <div class="row justify-center">
        <div class="col-12 col-lg-10">
          <div class="maincard">
            <div class="card1">
              <div class="row items-center q-pt-xl">
                <div class="col-3 head1 q-pl-xl">MNTN</div>
                <div class="col-6">
                  <div class="row text-center head2">
                    <div class="col-4" >Equipment</div>
                    <div class="col-4 ">About us</div>
                    <div class="col-4 ">Blog</div>
                  </div>
                </div>
                <div class="col-3 head3 text-right q-pr-xl">Account</div>
              </div>
              <div class="row items-center justify-center">
                <div class="column col-lg-6 col-md-6 sub_head">
                    <div class="text-left sub_head1">
                      <div class="row justify-left">
                      <span style="width:30px;height:.2px;background-color:#FBD784;margin:12px 25px 0 0"></span>
                      <span>A Hiking guide</span> 
                      </div>
                    </div>
                    <div class="text-left sub_head2">
                      Be prepared for the Mountains and beyond!
                    </div>
                </div>    
             </div>
            </div>

           <div class="card2" style="background: linear-gradient(180deg, rgba(11, 29, 38, 0) 0%, #0B1D26 61.38%);">
              <div class="row text-center item-center" style="background: linear-gradient(180deg, rgba(11, 29, 38, 0) 0%, #0B1D26 61.38%)">
                  <div class="col q-pr-xl" style="background: linear-gradient(180deg, rgba(11, 29, 38, 0) 0%, #0B1D26 61.38%);">
                    <div class="row justify-end">
                        <div class="col-12">
                          <div class="row justify-end">
                            <div class="column col-lg-8 col-md-8 card2_sub_head" >
                             <div class="card2_sub_heading">
                                <span class="row card2_head1">01</span>
                                <div class="sub_wrapper q-pl-lg">
                                    <div class="text-left card2_sub_head1">
                                      <div class="row justify-left">
                                        <span style="width:30px;height:.2px;background-color:#FBD784;margin:12px 25px 0 0"></span>
                                        <span> Get Started</span> 
                                      </div>
                                    </div>
                                    <div class="text-left card2_sub_head2">
                                      What level of hiker are you?
                                    </div>
                                    <p class="text-left card2_sub_head3">
                                      Determining what level of hiker you are can be an important tool when planning future hikes. This
                                      hiking level guide will help you plan hikes according to different hike ratings set by various 
                                      websites like All Trails and Modern Hiker. What type of hiker are you – novice, moderate, advanced
                                      moderate, expert, or expert backpacker?
                                    </p>
                                </div>
                             </div>
                            </div>    
                          </div>
                      </div>
                    </div>
                  </div>
                  <div class="col card2_head2 q-mt-md text-center item-center justify-center " style="background: linear-gradient(180deg, rgba(11, 29, 38, 0) 0%, #0B1D26 61.38%);">
                    <!-- <div class="col-6"><q-img src="../../src/assets/hillstations-in-kerala.jpg" style="height: 420px; max-width: 300px"></q-img></div> -->
                    <div class="row justify-center item-center " style="background: linear-gradient(180deg, rgba(11, 29, 38, 0) 0%, #0B1D26 61.38%);">
                        <div class="col-6 col-md-6 justify-center item-center text-center" style="background: linear-gradient(180deg, rgba(11, 29, 38, 0) 0%, #0B1D26 61.38%);"><q-img src="../../src/assets/hillstations-in-kerala.jpg" style="height: 440px; width: 22vw"></q-img></div>
                    </div>
                  </div>
              </div>
            </div>
            </div>

            <div class="card3">
              <div class="row text-center item-center">
                 <div class="col card2_head2 q-mt-md text-center item-center " style="background: linear-gradient(180deg, rgba(11, 29, 38, 0) 0%, #0B1D26 61.38%);">
                    <!-- <div class="col-6"><q-img src="../../src/assets/hillstations-in-kerala.jpg" style="height: 420px; max-width: 300px"></q-img></div> -->
                    <div class="row justify-center item-center q-mr">
                        <div class="col-6 col-md-6 justify-center item-center text-center"><q-img src="../../src/assets/hillstations-in-kerala.jpg" style="height: 440px; width: 22vw"></q-img></div>
                    </div>
                  </div>
                  <div class="col" >
                    <div class="row justify-start">
                        <div class="col-12 col-lg-8 col-md-8">
                          <div class="row justify-start" style="background: linear-gradient(180deg, rgba(11, 29, 38, 0) 0%, #0B1D26 61.38%);">
                            <div class="column col-lg-8 col-md-8 card2_sub_head" >
                              <span class="row card2_head1 q-mr-xl">02</span>
                              <div class="sub_wrapper q-pl-lg">
                                  <div class="text-left card2_sub_head1">
                                    <div class="row justify-left">
                                      <span style="width:30px;height:.2px;background-color:#FBD784;margin:12px 25px 0 0"></span>
                                      <span> Get Started</span> 
                                    </div>
                                  </div>
                                  <div class="text-left card2_sub_head2">
                                    What level of hiker are you?
                                  </div>
                                  <p class="text-left card2_sub_head3">
                                    Determining what level of hiker you are can be an important tool when planning future hikes. This
                                    hiking level guide will help you plan hikes according to different hike ratings set by various 
                                    websites like All Trails and Modern Hiker. What type of hiker are you – novice, moderate, advanced
                                    moderate, expert, or expert backpacker?
                                  </p>
                              </div>
                            </div>    
                          </div>
                      </div>
                    </div>
                  </div>
              </div>
            </div>

            <div class="card2">
              <div class="row text-center item-center">
                  <div class="col q-pr-xl" style="background: linear-gradient(180deg, rgba(11, 29, 38, 0) 0%, #0B1D26 61.38%);">
                    <div class="row justify-end">
                        <div class="col-12">
                          <div class="row justify-end">
                            <div class="column col-lg-8 col-md-8 col-sm-12 col-xs-12  card2_sub_head" >
                              <span class="row card2_head1 q-mr-xl">03</span>
                              <div class="sub_wrapper q-pl-lg">
                                    <div class="text-left card2_sub_head1">
                                      <div class="row justify-left">
                                        <span style="width:30px;height:.2px;background-color:#FBD784;margin:12px 25px 0 0"></span>
                                        <span> Get Started</span> 
                                      </div>
                                    </div>
                                    <div class="text-left card2_sub_head2">
                                      What level of hiker are you?
                                    </div>
                                    <p class="text-left card2_sub_head3">
                                      Determining what level of hiker you are can be an important tool when planning future hikes. This
                                      hiking level guide will help you plan hikes according to different hike ratings set by various 
                                      websites like All Trails and Modern Hiker. What type of hiker are you – novice, moderate, advanced
                                      moderate, expert, or expert backpacker?
                                    </p>
                              </div>
                            </div>    
                          </div>
                      </div>
                    </div>
                  </div>
                  <div class="col card2_head2 q-mt-md text-center item-center justify-center " style="background: linear-gradient(180deg, rgba(11, 29, 38, 0) 0%, #0B1D26 61.38%);">
                    <!-- <div class="col-6"><q-img src="../../src/assets/hillstations-in-kerala.jpg" style="height: 420px; max-width: 300px"></q-img></div> -->
                    <div class="row justify-center item-center q-mr">
                        <div class="col-6 col-md-6 justify-center item-center text-center"><q-img src="../../src/assets/hillstations-in-kerala.jpg" style="height: 440px; width: 22vw"></q-img></div>
                    </div>
                  </div>
              </div>
            </div>
            
        </div>
      </div>
    </q-page-container>
  </q-layout>
</template>

<script>
// import EssentialLink from 'components/EssentialLink.vue'

const linksData = [
  {
    title: 'Docs',
    caption: 'quasar.dev',
    icon: 'school',
    link: 'https://quasar.dev'
  },
  {
    title: 'Github',
    caption: 'github.com/quasarframework',
    icon: 'code',
    link: 'https://github.com/quasarframework'
  },
  {
    title: 'Discord Chat Channel',
    caption: 'chat.quasar.dev',
    icon: 'chat',
    link: 'https://chat.quasar.dev'
  },
  {
    title: 'Forum',
    caption: 'forum.quasar.dev',
    icon: 'record_voice_over',
    link: 'https://forum.quasar.dev'
  },
  {
    title: 'Twitter',
    caption: '@quasarframework',
    icon: 'rss_feed',
    link: 'https://twitter.quasar.dev'
  },
  {
    title: 'Facebook',
    caption: '@QuasarFramework',
    icon: 'public',
    link: 'https://facebook.quasar.dev'
  },
  {
    title: 'Quasar Awesome',
    caption: 'Community Quasar projects',
    icon: 'favorite',
    link: 'https://awesome.quasar.dev'
  }
]

export default {
  name: 'MainLayout',
  components: {
  },
  data () {
    return {
      leftDrawerOpen: false,
      essentialLinks: linksData
    }
  }
}
</script>
<style lang="sass" scoped>
.row
  // background: rgba(255,0,0,.1)
.row > div
  // padding: 10px 15px
  // background: linear-gradient(330.24deg, rgba(11, 29, 38, 0) 31.06%, #0B1D26 108.93%)
  // border: 1px solid rgba(86,61,124,.2)
.row + .row
  margin-top: 1rem
.maincard
  padding: 0
  background: url(../../src/assets/mountains-1590012_960_720.jpg)
  background-size: cover !important
  
.card1  
  padding: 0
  // background: url(../../src/assets/mountains-1590012_960_720.jpg)
  // background-size: cover !important
  height: 842px

.head2
  font-family: 'Gilroy'
  font-style: normal
  font-weight: 700
  font-size: 18px
  color: #FFFFFF

.head1
  font-family: 'Chronicle Display'
  font-size: 32px
  line-height: 38px
  letter-spacing: 0.01em
  text-transform: capitalize
  color: #FFFFFF

.head3
  font-family: 'Gilroy'
  font-size: 17px
  line-height: 21px
  color: #FFFFFF 

.sub_head
  margin-top: 100px

.sub_head1
  font-family: 'Gilroy'
  font-style: normal
  font-weight: 800
  font-size: 18px
  letter-spacing: 6px
  text-transform: uppercase
  color: #FBD784

.sub_head2
  font-family: 'Chronicle Display'
  font-style: normal
  font-weight: 600
  font-size: 50px
  text-transform: capitalize
  color: #FFFFFF

.card2
  height: 498px
  background-color: #0B1D26

.card2_head1
  height:120px
  width:120px
  font-family: 'Gilroy'
  font-style: normal
  font-weight: 800
  font-size: 140px
  line-height: 150px
  color: #FFFFFF
  opacity: 0.1
  position: absolute



.card2_head2
  height:360px
  width:283px

.card2_sub_head1
  font-family: 'Gilroy'
  font-style: normal
  font-weight: 800
  font-size: 18px
  letter-spacing: 6px
  text-transform: uppercase
  color: #FBD784
  position:relative

.card2_sub_head2
  font-family: 'Chronicle Display'
  font-style: normal
  font-weight: 600
  font-size: 30px
  text-transform: capitalize
  color: #FFFFFF 

.card2_sub_head3
  font-family: 'Gilroy'
  font-style: normal
  font-weight: 700
  font-size: 11px
  line-height: 32px
  color: #FFFFFF  

.card3
  height: 508px
  background-color: #0B1D26  

.sub_wrapper
 position: relative
 top: 65px
//  left: 48px
  </style>
