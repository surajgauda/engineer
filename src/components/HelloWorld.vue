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
          <div div class="row">
            <div class="table-section">
              <div class="col-sm-3" v-for="info in details" :key="info">
                <div class="card card-content">
                  <div class="bulb-icon">
                    <img v-bind:src="info.img" alt="" />
                  </div>
                  <div class="card-heading">{{ info.title }}</div>
                  <div class="card-para">
                    {{ info.header }}
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- engeering section Ending -->

    <!-- content section  -->

    <div class="bg-color-white">
      <div class="container">
        <div class="row">
          <div class="col-sm-6">
            <div class="collbrate-whole-content">
              <div class="card card-we">
                <div class="card-text">
                  we collabrate with brands and agencies to create memorable
                  experiences.
                </div>
              </div>
              <img src="@/assets/man.png" alt="" />
            </div>
          </div>
          <div class="col-sm-6">
            <div class="collbrate-whole-content">
              <div class="content-para text-bold">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa
                adipisci asperiores exercitationem repellat, totam dolorum,
                laboriosam perferendis qui autem eaque aspernatur. Aspernatur,
                assumenda veritatis facere modi odio eos quaerat nulla.
                <br /><br />
              </div>
              <div class="content-para">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa
                adipisci asperiores exercitationem repellat, totam dolorum,
                laboriosam perferendis qui autem eaque aspernatur. Aspernatur,
                assumenda veritatis facere modi odio eos quaerat nulla. Lorem
                ipsum, dolor sit amet consectetur <br /><br />
                adipisicing elit. Veritatis corrupti adipisci eaque accusantium
                aliquid eum ullam excepturi repellat, sapiente quo est, dolores
                atque? Corporis saepe eum tempore sapiente accusamus. Vel?
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="container">
        <div class="row">
          <div class="col-sm-6">
            <div class="collbrate-whole-content">
              <div class="content-para text-bold">Understanding Leadership</div>
              <div class="content-para">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa
                adipisci asperiores exercitationem repellat, totam dolorum,
                laboriosam perferendis qui autem eaque aspernatur. Aspernatur,
                assumenda veritatis facere modi odio eos quaerat nulla. Lorem
                ipsum, dolor sit amet consectetur <br /><br />
                adipisicing elit. Veritatis corrupti adipisci eaque accusantium
                aliquid eum ullam excepturi repellat, sapiente quo est, dolores
                atque? Corporis saepe eum tempore sapiente accusamus. Vel?
              </div>
              <div class="btn btn-lernmore">learn more</div>
            </div>
          </div>
          <div class="col-sm-6">
            <div class="collbrate-whole-content">
              <div class="women-img">
                <img src="@/assets/women.png" alt="" />
              </div>
            </div>
          </div>
        </div>
        <div class="mtt-whole-content collbrate-whole-content">
          <div class="eng-heading">meet the team</div>
          <div class="row">
            <div class="col-sm-4">
              <div class="card card-trans">
                <img src="@/assets/women2.png" alt="" width="80%" />
                <div class="card-heading">marry brown</div>
                <div class="leader-heading">creative leader</div>
                <div class="card-para">
                  Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                  Quidem, vitae quos vel soluta nam fugit fugiat debitis,
                </div>
                <div class="d-flex">
                  <a href="###"><i class="fa fa-facebook social-icon"></i></a>
                  <a href="###"><i class="fa fa-twitter social-icon"></i></a>
                  <a href="###"><i class="fa fa-instagram social-icon"></i></a>
                </div>
              </div>
            </div>
            <div class="col-sm-4">
              <div class="card card-trans">
                <img src="@/assets/women3.png" alt="" width="80%" />
                <div class="card-heading">ann richmond</div>
                <div class="leader-heading">creative leader</div>
                <div class="card-para">
                  Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                  Quidem, vitae quos vel soluta nam fugit fugiat debitis,
                </div>
                <div class="d-flex">
                  <a href="###"><i class="fa fa-facebook social-icon"></i></a>
                  <a href="###"><i class="fa fa-twitter social-icon"></i></a>
                  <a href="###"><i class="fa fa-instagram social-icon"></i></a>
                </div>
              </div>
            </div>
            <div class="col-sm-4">
              <div class="card card-trans">
                <img src="@/assets/men2.png" alt="" width="80%" />
                <div class="card-heading">Bob greenfeild</div>
                <div class="leader-heading">programming guru</div>
                <div class="card-para">
                  Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                  Quidem, vitae quos vel soluta nam fugit fugiat debitis,
                </div>
                <div class="d-flex">
                  <a href="###"><i class="fa fa-facebook social-icon"></i></a>
                  <a href="###"><i class="fa fa-twitter social-icon"></i></a>
                  <a href="###"><i class="fa fa-instagram social-icon"></i></a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- content section Ending -->

    <!-- engeering section -->

    <div class="bg-color-blue">
      <div class="container">
        <div class="leadership-whole-content">
          <div class="leadership-heading">$ 1,255,345</div>
          <div class="leadership-para">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Animi
            beatae nam in soluta,
          </div>
          <!-- <div class="leadership-para">
            perferendis doloremque quo eveniet ipsum cupiditate quidem.
          </div> -->
          <div div class="row">
            <div class="table-section">
              <div class="col-sm-3" v-for="info in details" :key="info">
                <div class="card card-content">
                  <div class="bulb-icon">
                    <img v-bind:src="info.img" alt="" />
                  </div>
                  <div class="card-heading">{{ info.title }}</div>
                  <div class="card-para">
                    {{ info.header }}
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- engeering section Ending -->
    <!-- corosel section  -->

    <div class="container">
      <div class="row">
        <div class="col-12 mx-auto">
          <div class="bordered">
            <div class="row mx-auto h-100">
              <div
                id="carousel-1"
                class="carousel slide w-100"
                data-ride="carousel"
              >
                <div class="carousel-inner h-100">
                  <div class="carousel-item active h-100">
                    <div class="col-4 h-100" id="pad">
                      <div class="card h-100 color-1"></div>
                    </div>
                  </div>
                  <div class="carousel-item h-100">
                    <div class="col-4 h-100" id="pad">
                      <div class="card h-100 color-2"></div>
                    </div>
                  </div>
                  <div class="carousel-item h-100">
                    <div class="col-4 h-100" id="pad">
                      <div class="card h-100 color-3"></div>
                    </div>
                  </div>
                  <div class="carousel-item h-100">
                    <div class="col-4 h-100" id="pad">
                      <div class="card h-100 color-4"></div>
                    </div>
                  </div>
                  <div class="carousel-item h-100">
                    <div class="col-4 h-100" id="pad">
                      <div class="card h-100 color-5"></div>
                    </div>
                  </div>
                </div>
                <a
                  class="carousel-control-prev"
                  href="movie-1.jpg"
                  role="button"
                  data-slide="prev"
                >
                  <span
                    class="carousel-control-prev-icon bg-dark rounded-circle"
                    aria-hidden="true"
                  ></span>
                  <span class="sr-only">Previous</span>
                </a>
                <a
                  class="carousel-control-next"
                  href="#carousel-1"
                  role="button"
                  data-slide="next"
                >
                  <span
                    class="carousel-control-next-icon bg-dark rounded-circle"
                    id="bordered-2"
                    aria-hidden="true"
                  ></span>
                  <span class="sr-only">Next</span>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- corsol section Ending -->
    <!-- FAQ section  -->
    <div class="bg-color-white">
      <div class="container">
        <div class="collbrate-whole-content">
          <div class="eng-heading">facts & questions</div>
          <div class="eng-para">
            Lorem ipsum, dolor sit amet consectetur adipisicing elit.
            Voluptatem,
          </div>
          <div class="container">
            <div class="accordion accordion-flush" id="accordionFlushExample">
              <div class="accordion-item">
                <h2 class="accordion-header" id="flush-headingOne">
                  <button
                    class="accordion-button collapsed"
                    type="button"
                    data-bs-toggle="collapse"
                    data-bs-target="#flush-collapseOne"
                    aria-expanded="false"
                    aria-controls="flush-collapseOne"
                  >
                    Do You provide Support?
                  </button>
                </h2>
                <div
                  id="flush-collapseOne"
                  class="accordion-collapse collapse"
                  aria-labelledby="flush-headingOne"
                  data-bs-parent="#accordionFlushExample"
                >
                  <div class="accordion-body">
                    Answer: Lorem, ipsum dolor sit amet consectetur adipisicing
                    elit. Hic dicta minus, quidem aperiam provident eos
                    veritatis quis labore suscipit aliquam harum, consectetur,
                    molestiae excepturi vero cupiditate esse quas recusandae
                    vel?
                  </div>
                </div>
              </div>
              <div class="accordion-item">
                <h2 class="accordion-header" id="flush-headingTwo">
                  <button
                    class="accordion-button collapsed"
                    type="button"
                    data-bs-toggle="collapse"
                    data-bs-target="#flush-collapseTwo"
                    aria-expanded="false"
                    aria-controls="flush-collapseTwo"
                  >
                    What Type of files I will get?
                  </button>
                </h2>
                <div
                  id="flush-collapseTwo"
                  class="accordion-collapse collapse"
                  aria-labelledby="flush-headingTwo"
                  data-bs-parent="#accordionFlushExample"
                >
                  <div class="accordion-body">
                    Answer: Lorem ipsum dolor sit, amet consectetur adipisicing
                    elit. Deserunt incidunt sit odio, nemo voluptas deleniti
                    repellat aliquam reiciendis quibusdam cupiditate
                    consequuntur iure voluptatem debitis minus, necessitatibus
                    sint exercitationem sapiente! Cupiditate!
                  </div>
                </div>
              </div>
              <div class="accordion-item">
                <h2 class="accordion-header d-flex" id="flush-headingThree">
                  <div
                    class="accordion-button collapsed"
                    type="button"
                    data-bs-toggle="collapse"
                    data-bs-target="#flush-collapseThree"
                    aria-expanded="false"
                    aria-controls="flush-collapseThree"
                  >
                    How to get future updates?
                  </div>
                  <div class="plus">
                    <a href="###"><i class="fa fa-plus plus-icon"></i></a>
                  </div>
                </h2>
                <div
                  id="flush-collapseThree"
                  class="accordion-collapse collapse"
                  aria-labelledby="flush-headingThree"
                  data-bs-parent="#accordionFlushExample"
                >
                  <div class="accordion-body">
                    Answer: Lorem ipsum dolor sit, amet consectetur adipisicing
                    elit. Suscipit eius similique saepe quos eveniet, tempora
                    beatae perspiciatis modi nam autem cumque cum voluptatum
                    error officia explicabo inventore. Voluptate, sit nam.
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- FAQ section Ending -->
    <div class="bg-color-blue">
      <div class="container">
        <div class="leadership-whole-content">
          <div class="number-head">(480) 565-7878</div>
          <div class="address-para">
            4140 PARKER RD. AllENTOWN , NEW MEXICO 56674 <br /><br />
          </div>
          <div class="time-para">
            Tuesday - Friday:8am- 7pm <br />
            Sataurday - Sunday : 8am - 10pm <br />
            Colsed Monday
          </div>
          <div class="d-flex">
            <a href="###"
              ><i class="fa fa-facebook social-icon color-white"></i
            ></a>
            <a href="###"
              ><i class="fa fa-twitter social-icon color-white"></i
            ></a>
            <a href="###"
              ><i class="fa fa-instagram social-icon color-white"></i
            ></a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  data() {
    return {
      details: [
        {
          img: "data:image/png;base64,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",
          title: "motivation",
          header:
            " Lorem, ipsum dolor sit amet consectetur adipisicin Lorem ipsum dolor sit amet consectetur",
        },
        {
          img: "data:image/png;base64,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",
          title: "Creativity",
          header:
            " Lorem, ipsum dolor sit amet consectetur adipisicin Lorem ipsum dolor sit amet consectetur ",
        },
        {
          img: "data:image/png;base64,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",
          title: "Postivity",
          header:
            " Lorem, ipsum dolor sit amet consectetur adipisicin Lorem ipsum dolor sit amet consectetur ",
        },
        {
          img: "data:image/png;base64,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",
          title: "Delegating",
          header:
            " Lorem, ipsum dolor sit amet consectetur adipisicin Lorem ipsum dolor sit amet consectetur ",
        },
      ],
    };
  },
};
</script>
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
  text-align: left;
}
.eng-whole-content {
  text-align: left;
  padding-bottom: 25px;
}
.eng-para {
  text-align: left;
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
  padding: 60px 12px 60px 20px;
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
  border-radius: 13px;
  padding: 20px 20px 60px 20px;
}
.card-heading {
  color: #7db6c8;
  font-size: 20px;
  font-weight: 700;
  padding: 15px 0px;
  text-transform: uppercase;
  text-align: left;
  letter-spacing: 2px;
}
.card-para {
  font-size: 21px;
  line-height: 29px;
  text-align: left;
}

/* Content */
.collbrate-whole-content {
  padding: 60px 12px 60px 12px;
}
.card-trans {
  border-color: transparent;
}
.card-we {
  background-color: #f2f2f2;
  font-size: 22px;
  font-weight: bold;
  text-transform: uppercase;
  text-align: left;
  color: #000000;
  width: 50%;
  padding: 12px 12px 12px 12px;
}
.content-para {
  font-size: 18px;
  text-align: left;
  width: 80%;
}
.text-bold {
  font-weight: bold;
}
.leader-heading {
  font-size: 18px;
  text-align: left;
  font-weight: 800;
  padding-bottom: 12px;
}
.social-icon {
  color: #7db6c8;
  padding: 30px 5px 12px 5px;
  font-size: 25px;
}
/* corsel */
.carousel-inner .carousel-item.active,
.carousel-inner .carousel-item-next,
.carousel-inner .carousel-item-prev {
  display: flex;
}
.carousel-inner .carousel-item-right.active,
.carousel-inner .carousel-item-next {
  transform: translateX(33.333%);
}

.carousel-inner .carousel-item-left.active,
.carousel-inner .carousel-item-prev {
  transform: translateX(-33.333%);
}
.carousel-inner .carousel-item {
  transition: transform 1.5s ease;
}
.carousel-inner .carousel-item-right,
.carousel-inner .carousel-item-left {
  transform: translateX(0);
}
#pad {
  padding-left: 5px;
  padding-right: 5px;
}
.color-1 {
  background-image: url("@/assets/women.png");
}
.color-2 {
  background-image: url("@/assets/women2.png");
}
.color-3 {
  background-image: url("@/assets/women3.png");
}
.color-4 {
  background-image: url("@/assets/men2.png");
}
.color-5 {
  background-image: url("@/assets/women.png");
}
.bordered {
  border: rgb(220, 220, 220) medium solid;
  border-radius: 10px;
  padding: 5px 5px 5px 5px;
  height: 31rem;
}
.overlay {
  z-index: 1;
  padding: 0;
  border: none;
  background: rgba(68, 68, 68, 0.5);
}
/* corosel ending */
.support-box {
  /* background-color: #f2f2f2; */
  display: flex;
  justify-content: space-between;
  padding: 20px 12px 20px 12px;
}
.support-box:hover {
  background-color: #f2f2f2;
  display: flex;
  justify-content: space-between;
  padding: 20px 12px 20px 12px;
}
.support-para {
  color: #7db6c8;
  font-weight: 700;
  font-size: 22px;
  padding-top: 12px;
}
.plus {
  width: 50px;
  height: 50px;
  background-color: #7db6c8;
  border-radius: 50%;
  padding: 9px;
}
.plus-icon {
  font-size: 21px;
  color: #ffffff;
  background-color: #7db6c8;
}
.accordion-button::after {
  background-color: #7db6c8;
  border-radius: 50%;
}
/* Dropdown */
.accordion-button {
  font-size: 22px;
  color: #7db6c8;
}
.accordion-body {
  font-size: 20px;
  text-align: left;
  padding: 15px 10px 15px 10px;
}
.accordion-button::after {
  color: #7db6c8;
}
/* Footer section */
.number-head {
  color: #ffffff;
  font-size: 40px;
  font-weight: 800;
}
.address-para {
  color: white;
  font-size: 22px;
}
.time-para {
  color: white;
  font-size: 20px;
  font-weight: 700;
}
.color-white {
  color: #ffffff;
  padding: 30px 5px 12px 5px;
  font-size: 35px;
}
</style>
