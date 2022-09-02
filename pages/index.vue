<template>
  <div class=" py-4 pb-8" :class="{'px-8' : $vuetify.breakpoint.mdAndUp}">
    <v-row>
      <v-col md="8">
        <v-card class="rounded-lg" outlined>
          <div :class="{'pa-4' : $vuetify.breakpoint.smAndDown}">

            <v-img :src="require('~/static/assets/wedding.png')"></v-img>
          </div>
          <v-card
            color="#E0F2FF"
            height="28px"
            class="
              d-flex
              rounded-0
              info-line
              font-weight-bold
              justify-space-between
              px-6
              align-center
            "
            flat
          >
            <p class="mb-0"><span>Organised by:</span> Mustapha Mohammed</p>

            <p class="mb-0">One-Off</p>
          </v-card>

          <div class="mx-6 py-2 info-box d-flex justify-space-between">
            <p class="mb-0 d-flex"> <img src="~/static/assets/tag.svg" class="mr-1" alt=""> Ceremony</p>
            <p class="mb-0"><span>10 days left</span></p>
          </div>
          <div class="pa-6">
            <h2 class="font-weight-medium">Bless Chike and Shayo’s wedding</h2>
            <p class="description mt-4">
              I need to raise 5 million naira for a wedding ceremony, that is
              scheduled to hold on the 26th June 2020, i need this money to
              support this couple and their newly born quadruplets in th...<b
                >See more</b
              >
            </p>
          </div>

          <v-tabs>
            <v-tabs-slider></v-tabs-slider>
            <v-tab>Overview</v-tab>
            <v-tab>Blessors</v-tab>
            <v-tab>Rewards</v-tab>
            <v-tab>Comments</v-tab>

            <v-tab-item class="pa-6">
              <div class="d-flex justify-space-between">
                <h3 class="font-weight-medium">Updates</h3>

                <p class="mb-0" style="font-size: 12px">
                  View all
                  <font-awesome-icon
                    :icon="['fas', 'chevron-right']"
                  ></font-awesome-icon>
                </p>
              </div>

              <p class="update-text">
                I need to raise 5 million naira for a wedding ceremony, that is
                scheduled to hold on the 26th June 2020, i need this money to
                support this couple and their newly born quadruplets in the
                earliest stages of their life.
              </p>
              <p class="update-text">
                I appreaciate every little amount that you can use to bless
                me.<br /><nuxt-link
                  to="#"
                  style="font-weight: bold; color: #161722"
                  >Read More.</nuxt-link
                >
              </p>
              <v-divider class="my-4"></v-divider>
              <h3 class="font-weight-medium">Fundraiser Members</h3>
              <v-row class="mt-4">
                <v-col md="6">
                  <div class="d-flex align-center">
                    <div class="dp dp--one d-flex justify-center align-center">
                      HJ
                    </div>
                    <div class="ml-4">
                      <p class="mb-0 p-12"><span>Organiser</span></p>
                      <p class="mb-0 p-12 font-weight-bold">
                        Fawale Gbolahan T
                      </p>
                    </div>
                  </div>

                  <div class="d-flex align-center mt-6">
                    <div class="dp dp--two d-flex justify-center align-center">
                      LK
                    </div>
                    <div class="ml-4">
                      <p class="mb-0 p-12"><span>Observer</span></p>
                      <p class="mb-0 p-12 font-weight-bold">
                        Fawale Gbolahan T
                      </p>
                    </div>
                  </div>
                </v-col>

                <v-col md="6">
                  <div class="d-flex align-center">
                    <div
                      class="dp dp--three d-flex justify-center align-center"
                    >
                      GB
                    </div>
                    <div class="ml-4">
                      <p class="mb-0 p-12"><span>Beneficiary</span></p>
                      <p class="mb-0 p-12 font-weight-bold">
                        Fawale Gbolahan T
                      </p>
                    </div>
                  </div>

                  <div class="d-flex align-center mt-6">
                    <div class="dp dp--four d-flex justify-center align-center">
                      EM
                    </div>
                    <div class="ml-4">
                      <p class="mb-0 p-12"><span>Observer</span></p>
                      <p class="mb-0 p-12 font-weight-bold">
                        Fawale Gbolahan T
                      </p>
                    </div>
                  </div>
                </v-col>
              </v-row>
              <v-divider class="my-4"></v-divider>
              <h3 class="font-weight-medium">Fundraiser on Social Media</h3>

              <div class="d-flex mt-3">
                <font-awesome-icon
                  class="social-icon"
                  :icon="['fab', 'facebook']"
                ></font-awesome-icon>

                <font-awesome-icon
                  class="social-icon ml-3"
                  :icon="['fab', 'instagram']"
                ></font-awesome-icon>

                <font-awesome-icon
                  class="social-icon ml-3"
                  :icon="['fab', 'twitter']"
                ></font-awesome-icon>

                <font-awesome-icon
                  class="social-icon ml-3"
                  :icon="['fab', 'youtube']"
                ></font-awesome-icon>
              </div>
              <v-divider class="my-4"></v-divider>
              <p class="p-12 font-weight-medium">
                <span>Fundraiser ID: </span> 548757458ID
              </p>
              <div class="d-flex justify-space-between">
                <div class="d-flex">
                  <div>
                    <img src="~/static/assets/flag.svg" alt="" />
                  </div>
                  <nuxt-link to="#">
                    <p class="p-14 ml-2 mb-0">Report Project</p>
                  </nuxt-link>
                </div>

                <p class="p-14">
                  <span
                    ><font-awesome-icon
                      :icon="['fas', 'heart']"
                      class="mr-1"
                    ></font-awesome-icon
                    >2.3k</span
                  >
                </p>
              </div>
            </v-tab-item>
          </v-tabs>
        </v-card>
      </v-col>
      <v-col md="4">
        <v-card outlined class="rounded-lg pa-6">
          <div class="d-flex justify-space-between">
            <p class="mb-0 font-weight-bold p-12">N2,000,320,000</p>
            <p class="mb-0 p-12 font-weight-bold">N5,000,000,000</p>
          </div>
          <v-progress-linear
            :value="35"
            color="#567286"
            background-color="#E0F2FF"
            class="mt-3 rounded"
            height="8px"
          ></v-progress-linear>
          <div class="d-flex mt-2 justify-space-between">
            <p class="mb-0 p-12"><span>Raised</span></p>
            <p class="mb-0 p-12"><span>Target</span></p>
          </div>
          <v-divider class="my-4"></v-divider>
          <p class="p-12">
            Bless this Fundraiser by making a transfer to the bank account below
            or use the <b> “Bless”</b> button.
          </p>

          <v-card
            class="
              rounded
              flex-column
              acct-details
              d-flex
              align-center
              justify-center
            "
            flat
            height="102"
            color="#567286"
          >
            <p class="p-12 mb-0 light--text font-weight-bold">STERLING BANK</p>
            <h3 class="white--text font-weight-bold">
              0046748389 <img src="~/static/assets/copy.svg" alt="" />
            </h3>
            <p class="p-12 mb-0 white--text font-weight-bold">
              Gbolahan Fawale
            </p>
          </v-card>
          <div class="pt-8 text-center">
            <center>
              <v-divider></v-divider>
              <p
                style="
                  font-size: 14px;
                  color: #7e7b7b;
                  font-weight: 600;
                  margin-top: -20px;
                  width: 40px;
                "
                class="text-center white pa-2"
              >
                Or
              </p>
            </center>
          </div>
          <p class="p-12">
            You can also bless this fundraiser from anywhere in the world by
            using Paypal or Card.
          </p>

          <v-card height="75" class="d-flex justify-center align-center pay-card">
            <img src="~/static/assets/PayPal.svg" alt="">
          </v-card>

          <v-card height="75" class="d-flex justify-center mt-6 align-center pay-card">
            <img src="~/static/assets/MasterCard_Logo.svg" alt="">
            <img class="ml-1" src="~/static/assets/Visa_Inc._logo 2.svg" alt="">
            <img class="ml-1" src="~/static/assets/Verve Logo (1) 2.svg" alt="">
            <img class="ml-1" src="~/static/assets/UnionPay_logo 1.svg" alt="">
          </v-card>
          <v-btn color="#3E3C3C" height="48" class="rounded mt-9 elevation-0 " block >
            <p class="p-14 font-weight-bold white--text mb-0 ">Share this Fundraiser</p>
          </v-btn>
        </v-card>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
<style lang="scss" scoped>
.info-line {
  font-size: 10px;
  p {
    color: #161722;
    span {
      color: #7e7b7b;
    }
  }
}
.info-box {
  border-bottom: 1px solid #e5e5e5;
  p {
    font-size: 12px;
    color: #161722;
    font-weight: 600;
    span {
      color: #7e7b7b;
    }
  }
}
h3 {
  color: #161722;
}

.description {
  font-family: 'Montserrat';
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 20px;
  /* or 143% */

  color: #161722;
}
.update-text {
  font-family: 'Montserrat';
  font-style: normal;
  font-weight: 400;
  font-size: 12px;
  line-height: 18px;
  /* or 150% */

  color: #161722;
}
.dp {
  width: 40px;
  height: 40px;
  border-radius: 100%;
  font-family: 'Montserrat';
  font-style: normal;
  font-weight: 700;
  font-size: 14px;
  line-height: 17px;
  /* identical to box height */

  letter-spacing: 0.02em;
  &--one {
    color: #567286;
    background: #e0f2ff;
  }
  &--two {
    background: #e8f5ff;
    color: #1f90e1;
  }
  &--three {
    background: #ffe3e7;
    color: #a0616a;
  }
  &--four {
    background: #e3e2ff;
    color: #545384;
  }
}
.p-12 {
  font-size: 12px;
  color: #161722;
  span {
    color: #7e7b7b;
  }
}
.p-14 {
  font-weight: 500;
  font-size: 14px;
  color: #161722;
  span {
    color: #fd5f5f;
  }
}
.social-icon {
  font-size: 24px;
  color: #577387;
}
a {
  color: #161722 !important;
}
.acct-details {
  .light--text {
    color: #e0f2ff !important;
  }
}

.pay-card {
  background: #ffffff;
  border: 1px solid #e5e5e5;
  box-shadow: 0px 1px 4px rgba(0, 0, 0, 0.08) !important;
  border-radius: 4px;
}
</style>