<template>
  <section>
    <div class="bg-img">
      <div class="container">
        <div class="heding-content d-flex">
          <div class="banner-text">
            <div class="d-flex number-para">
              <div class="number">01</div>
              <div class="number-text">
                Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                Doloremque perferendis debitis.
              </div>
            </div>
            <div class="heading-para">
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Vel
              voluptatem eveniet, voluptas, harum soluta amet quibusdam
              distinctio sequi dignissimos ut, dolor laudantium. Nihil ipsam
              error veritatis iusto vitae veniam dolor.
            </div>
          </div>
          <div class="building">
            <!-- <img src="@/assets/building-img.png" alt="###" /> -->
          </div>
        </div>
      </div>
    </div>

    <!-- engeering section -->

    <div class="bg-color-white">
      <div class="container">
        <div class="row">
          <div class="col-sm-8">
            <div class="container eng-whole-content">
              <div class="eng-heading">and engineering firm</div>
              <div class="eng-para">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod
                ipsa quia error tenetur excepturi, nobis ea sit saepe at
                sapiente totam animi aperiam. Dignissimos quod commodi aliquam
                optio itaque ab!
              </div>
              <div class="btn btn-lernmore">learn more</div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- engeering section -->

    <div class="bg-color-blue">
      <div class="container">
        <div class="leadership-whole-content">
          <div class="leadership-heading">Important leadership Skills</div>
          <div class="leadership-para">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Animi
            beatae nam in soluta,
          </div>
          <div class="leadership-para">
            perferendis doloremque quo eveniet ipsum cupiditate quidem.
          </div>
          <div class="row">
            <div class="col-sm-3">
              <div class="card card-content">
                <div class="bulb-icon"><img src="" alt="" /></div>
                <div class="card-heading">motivation</div>
                <div class="card-para">
                  Lorem, ipsum dolor sit amet consectetur adipisicin
                </div>
              </div>
            </div>
            <div class="col-sm-3">
              <div class="card card-content">
                <div class="bulb-icon"><img src="" alt="" /></div>
                <div class="card-heading">Creativity</div>
                <div class="card-para">
                  Lorem, ipsum dolor sit amet consectetur adipisicin
                </div>
              </div>
            </div>
            <div class="col-sm-3">
              <div class="card card-content">
                <div class="bulb-icon"><img src="" alt="" /></div>
                <div class="card-heading">postivity</div>
                <div class="card-para">
                  Lorem, ipsum dolor sit amet consectetur adipisicin
                </div>
              </div>
            </div>
            <div class="col-sm-3">
              <div class="card card-content">
                <div class="bulb-icon"><img src="" alt="" /></div>
                <div class="card-heading">delegating</div>
                <div class="card-para">
                  Lorem, ipsum dolor sit amet consectetur adipisicin
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<style>
.bg-img {
  background-image: url("@/assets/building-img.png");
  background-repeat: no-repeat;
  background-position: right top;
  background-color: #63a1b6;
  height: 673px;
}
.heding-content {
  width: 50%;
  text-align: left;
}
.banner-text {
  padding: 60px 20px 12px 20px;
  width: 450px;
  color: #ffffff;
}
.number-para {
  padding-bottom: 12px;
  color: #ffffff;
}
.number {
  width: 100px;
  background-color: white;
  color: skyblue;
  font-size: 70px;
  font-weight: 700;
  padding: 5px;
}
.number-text {
  color: #ffffff;
  font-size: 14px;
  vertical-align: bottom;
  padding: 55px 17px 0px 25px;
}
.heading-para {
  text-align: left;
  font-weight: 700;
}

/* engeering heading */
.eng-heading {
  padding: 50px 12px 20px 20px;
  font-size: 51px;
  font-weight: 800;
}
.eng-whole-content {
  text-align: left;
  padding-bottom: 25px;
}
.eng-para {
  font-size: 20px;
  font-weight: 100;
  padding: 12px 12px 20px 20px;
}
.btn-lernmore {
  background-color: #7db6c8;
  text-transform: uppercase;
  border-radius: 18px;
  padding: 12px;
  width: 143px;
  color: #ffffff;
  font-size: 13px;
  margin: 12px 12px 20px 20px;
}
/* Leadership Skills */
.bg-color-blue {
  background-color: #7db6c8;
}
.leadership-whole-content {
  text-align: left;
  padding: 60px 12px 30px 20px;
}
.leadership-heading {
  color: #ffffff;
  font-size: 40px;
  font-weight: 800;
  padding-bottom: 30px;
}
.leadership-para {
  color: #ffffff;
  font-size: 21px;
}
.card-content {
  margin: 40px 0px 0px 0px;
}
</style>
