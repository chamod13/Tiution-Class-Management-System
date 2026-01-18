<template>
  <q-page>
    <!-- Hero Section -->
    <section class="hero-section text-center relative-position">
      <div class="circle-bg-1"></div>
      <div class="container relative-position z-top">
        <div class="q-mb-md">
          <q-badge
            color="grey-2"
            text-color="black"
            class="q-px-md q-py-sm rounded-badge text-weight-bold shadow-1"
          >
            New: Version 2.0 Released
          </q-badge>
        </div>

        <h1 class="text-h2 text-weight-bolder q-mb-lg hero-title text-black">
          The Ultimate <span class="text-secondary">Tuition Management</span><br />
          Solution.
        </h1>

        <p class="text-grey-8 text-h5 q-mb-xl hero-subtitle weight-medium">
          Streamline your entire tuition class workflow. From student enrollment to automated
          payments and attendance tracking.
        </p>

        <div class="row justify-center q-gutter-md q-mb-xl">
          <q-btn
            unelevated
            color="black"
            text-color="white"
            size="lg"
            label="Start Free Trial"
            no-caps
            class="q-px-xl q-py-sm rounded-borders text-weight-bold"
          />
          <q-btn
            outline
            color="black"
            size="lg"
            no-caps
            class="q-px-xl q-py-sm rounded-borders text-weight-bold"
          >
            <q-icon left name="play_circle" />
            <div>Watch Demo</div>
          </q-btn>
        </div>

        <!-- Hero Image Wrapper -->
        <div class="hero-image-container q-mx-auto shadow-22 rounded-xl overflow-hidden bg-white">
          <q-img
            src="../assets/tuition_hero_modern_1768725635182.png"
            class="hero-image"
            fit="cover"
            position="50% 20%"
          />
        </div>
      </div>
    </section>

    <!-- Stats Section -->
    <section class="q-py-xl bg-white stats-section border-section">
      <div class="container">
        <div class="row q-col-gutter-lg justify-center text-center">
          <div class="col-12 col-md-3">
            <div class="text-h2 text-weight-bold text-black number-font">500+</div>
            <div class="text-subtitle1 text-grey-7 text-weight-medium">Classes Managed</div>
          </div>
          <div class="col-12 col-md-3">
            <div class="text-h2 text-weight-bold text-black number-font">50k+</div>
            <div class="text-subtitle1 text-grey-7 text-weight-medium">Active Students</div>
          </div>
          <div class="col-12 col-md-3">
            <div class="text-h2 text-weight-bold text-black number-font">99%</div>
            <div class="text-subtitle1 text-grey-7 text-weight-medium">Efficiency Boost</div>
          </div>
        </div>
      </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="q-py-xl section-padding bg-grey-1">
      <div class="container">
        <div class="text-center q-mb-xl">
          <h2 class="text-h3 text-weight-bold q-mb-md text-black">Everything you need</h2>
          <p class="text-grey-7 text-h6" style="max-width: 600px; margin: 0 auto">
            All the tools to manage your tuition class in one place, designed for speed and
            simplicity.
          </p>
        </div>

        <div class="row q-col-gutter-xl items-center">
          <div class="col-12 col-md-6">
            <div class="shadow-15 rounded-borders overflow-hidden bg-white">
              <q-img
                src="../assets/tuition_dashboard_feature_1768725657605.png"
                class="full-width"
                style="min-height: 400px"
              />
            </div>
          </div>
          <div class="col-12 col-md-6">
            <div class="q-gutter-y-lg">
              <div class="feature-card q-pa-lg rounded-borders bg-white shadow-1 cursor-pointer">
                <div class="row items-center no-wrap">
                  <div class="bg-black text-white q-pa-md rounded-borders q-mr-lg flex flex-center">
                    <q-icon name="group" size="sm" />
                  </div>
                  <div>
                    <div class="text-h6 text-weight-bold q-mb-xs">Student Management</div>
                    <div class="text-grey-7 text-body1">
                      Easily enroll, track, and manage student profiles and history with a few
                      clicks.
                    </div>
                  </div>
                </div>
              </div>

              <div class="feature-card q-pa-lg rounded-borders bg-white shadow-1 cursor-pointer">
                <div class="row items-center no-wrap">
                  <div class="bg-black text-white q-pa-md rounded-borders q-mr-lg flex flex-center">
                    <q-icon name="qr_code" size="sm" />
                  </div>
                  <div>
                    <div class="text-h6 text-weight-bold q-mb-xs">Smart Attendance</div>
                    <div class="text-grey-7 text-body1">
                      QR code based instant attendance marking with automated SMS notifications to
                      parents.
                    </div>
                  </div>
                </div>
              </div>

              <div class="feature-card q-pa-lg rounded-borders bg-white shadow-1 cursor-pointer">
                <div class="row items-center no-wrap">
                  <div class="bg-black text-white q-pa-md rounded-borders q-mr-lg flex flex-center">
                    <q-icon name="payments" size="sm" />
                  </div>
                  <div>
                    <div class="text-h6 text-weight-bold q-mb-xs">Automated Payments</div>
                    <div class="text-grey-7 text-body1">
                      Track tuition fees, issue digital receipts, and manage outstanding payments
                      effortlessly.
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Call to Action -->
    <section class="q-py-xl bg-black text-white text-center">
      <div class="container q-py-xl">
        <h2 class="text-h3 text-weight-bold q-mb-lg">Ready to upgrade your institute?</h2>
        <p
          class="text-h6 text-grey-4 q-mb-xl"
          style="max-width: 600px; margin-left: auto; margin-right: auto"
        >
          Join hundreds of other tuition masters who are saving time and growing their classes with
          EduMaster.
        </p>
        <q-btn
          unelevated
          color="white"
          text-color="black"
          size="lg"
          label="Get Started Now"
          no-caps
          class="q-px-xl q-py-sm rounded-borders text-weight-bold"
        />
      </div>
    </section>
  </q-page>
</template>

<script setup></script>

<style scoped>
/* Scoped Styles for IndexPage */
.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 24px;
}
.hero-section {
  padding-top: 160px;
  padding-bottom: 100px;
  background: radial-gradient(circle at 50% 10%, #fcfcfc, #ffffff);
  overflow: hidden;
}

.hero-title {
  line-height: 1.2;
  letter-spacing: -1.5px;
  font-size: 3.5rem;
}

.hero-subtitle {
  max-width: 700px;
  margin-left: auto;
  margin-right: auto;
  line-height: 1.6;
}

.rounded-borders {
  border-radius: 12px;
}

.rounded-badge {
  border-radius: 50px;
}

/* Secondary accent text */
.text-secondary {
  color: #4a4a4a;
}

.shadow-22 {
  box-shadow: 0 30px 60px -15px rgba(0, 0, 0, 0.15);
}

.shadow-15 {
  box-shadow: 0 20px 40px -10px rgba(0, 0, 0, 0.1);
}

.rounded-xl {
  border-radius: 24px;
}

.feature-card {
  transition:
    transform 0.3s ease,
    box-shadow 0.3s ease;
  border: 1px solid rgba(0, 0, 0, 0.03);
}

.feature-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 15px 30px -5px rgba(0, 0, 0, 0.1) !important;
  border-color: rgba(0, 0, 0, 0);
}

.circle-bg-1 {
  position: absolute;
  top: -25%;
  left: 50%;
  transform: translateX(-50%);
  width: 140%;
  height: 900px;
  background: radial-gradient(circle, rgba(0, 0, 0, 0.02) 0%, rgba(255, 255, 255, 0) 65%);
  z-index: 0;
  pointer-events: none;
}

.border-section {
  border-top: 1px solid #f0f0f0;
  border-bottom: 1px solid #f0f0f0;
}

.hero-image-container {
  max-width: 1000px;
  height: 500px;
}

.hero-image-container .q-img {
  height: 100%;
}

@media (max-width: 599px) {
  .hero-title {
    font-size: 2.5rem;
  }
  .hero-image-container {
    height: 300px;
  }
}
</style>
