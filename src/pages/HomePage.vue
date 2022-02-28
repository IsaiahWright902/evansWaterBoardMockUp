<template>
  <div class="container-fluid hero">
    <Navbar></Navbar>
    <div class="container">
      <div class="row title-spacing">
        <div class="col-12 text-center">
          <h1 class="page-heading">Evans Water Board</h1>
          <p class="heading-text">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint
            aperiam repudiandae cumque, cupiditate tenetur quis? Labore fugiat
            delectus, vitae et assumenda porro amet a accusamus ipsum impedit
            expedita sequi qui!
          </p>
        </div>
      </div>
    </div>
  </div>
  <div class="container pt-5">
    <div class="row">
      <div class="col-12">
        <h2 class="section-heading">News</h2>
      </div>
    </div>
    <div class="row pt-2">
      <div class="col-12">
        <div class="card">
          <div class="card-body">
            <p class="newsViewAll">
              View All
              <img
                class="img-fluid"
                style="width: 20px"
                src="../assets/img/vector-link.png"
                alt=""
              />
            </p>
            <div class="row">
              <div class="col-12">
                <p>
                  2/28/2022 <br />
                  <strong>We got something new</strong>
                </p>
              </div>
            </div>
            <div class="row">
              <div class="col-12">
                <p>
                  Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                  Dolore ab nam soluta asperiores vero porro quo eligendi facere
                  laboriosam consequatur praesentium fugit pariatur facilis,
                  libero dolorem ullam earum quod natus?
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="row pt-4">
      <div class="col-12">
        <div class="card">
          <div class="card-body">
            <p class="newsViewAll">
              View All
              <img
                class="img-fluid"
                style="width: 20px"
                src="../assets/img/vector-link.png"
                alt=""
              />
            </p>
            <div class="row">
              <div class="col-12">
                <p>
                  2/28/2022 <br />
                  <strong>We got something new</strong>
                </p>
              </div>
            </div>
            <div class="row">
              <div class="col-12">
                <p>
                  Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                  Dolore ab nam soluta asperiores vero porro quo eligendi facere
                  laboriosam consequatur praesentium fugit pariatur facilis,
                  libero dolorem ullam earum quod natus?
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="row pt-4">
      <div class="col-12">
        <div class="card">
          <div class="card-body">
            <p class="newsViewAll">
              View All
              <img
                class="img-fluid"
                style="width: 20px"
                src="../assets/img/vector-link.png"
                alt=""
              />
            </p>

            <div class="row">
              <div class="col-12">
                <p>
                  2/28/2022 <br />
                  <strong>We got something new</strong>
                </p>
              </div>
            </div>
            <div class="row">
              <div class="col-12">
                <p>
                  Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                  Dolore ab nam soluta asperiores vero porro quo eligendi facere
                  laboriosam consequatur praesentium fugit pariatur facilis,
                  libero dolorem ullam earum quod natus?
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="container pt-5">
    <div class="row pt-5">
      <div class="col-12">
        <h2 class="section-heading">Latest Water Tests</h2>
      </div>
    </div>
    <div class="row">
      <div class="col-12">
        <table class="table">
          <thead>
            <tr>
              <th scope="col">Date</th>
              <th scope="col">PH</th>
              <th scope="col">Bacteria</th>
              <th scope="col">Lead</th>
              <th scope="col">Chlorine</th>
              <th scope="col">Nitrates</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>2/28/22</td>
              <td>99</td>
              <td>99</td>
              <td>99</td>
              <td>99</td>
              <td>99</td>
            </tr>
          </tbody>
          <tbody>
            <tr>
              <td>2/28/22</td>
              <td>99</td>
              <td>99</td>
              <td>99</td>
              <td>99</td>
              <td>99</td>
            </tr>
          </tbody>
          <tbody>
            <tr>
              <td>2/28/22</td>
              <td>99</td>
              <td>99</td>
              <td>99</td>
              <td>99</td>
              <td>99</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
  <div class="container pt-5">
    <div class="row pt-5">
      <div class="col-12">
        <h2 class="section-heading">
          Questions or Concerns? <br />
          Get in touch today!
        </h2>
      </div>
    </div>
    <div class="row">
      <div class="col-12">
        <div class="row">
          <form onsubmit="sendMail(event)">
            <div class="form-margin">
              <div class="row">
                <div
                  class="col-md-6"
                  data-aos="fade-right"
                  data-aos-delay="1000"
                  data-aos-once="true"
                >
                  <p class="form-label">Name</p>
                  <input
                    id="contact-name"
                    required
                    type="text"
                    class="form-control"
                  />
                </div>
                <div
                  class="col-md-6"
                  data-aos="fade-left"
                  data-aos-delay="1000"
                  data-aos-once="true"
                >
                  <p class="form-label">Email</p>
                  <input
                    id="contact-email"
                    required
                    type="text"
                    class="form-control"
                  />
                </div>
              </div>

              <div class="row pt-3">
                <div
                  class="col-12"
                  data-aos="fade-up"
                  data-aos-delay="1000"
                  data-aos-once="true"
                >
                  <p class="form-label">Message</p>
                  <textarea
                    class="form-control"
                    id="contact-message"
                    cols="100"
                    rows="100"
                    style="height: 15vh"
                  ></textarea>
                </div>
              </div>
              <div class="row pt-4">
                <div
                  class="col-12 text-center"
                  data-aos="fade-up"
                  data-aos-delay="1000"
                  data-aos-once="true"
                >
                  <button
                    id="form-button"
                    type="submit"
                    class="styled-btn styled-btn--create"
                  >
                    Contact Now!
                  </button>
                </div>
              </div>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>
  <div class="container pt-5"></div>
  <Footer />

  <!-- Dev Spacing -->
</template>

<script>
import { computed, onMounted, reactive } from "vue";
import Navbar from "../components/Navbar.vue";
import Footer from "../components/Footer.vue";
export default {
  name: "Home",
  setup() {
    const state = reactive({});
    return {
      state,
    };
  },
  components: {
    Navbar,
    Footer,
  },
};
</script>

<style lang="scss">
@import "../assets/scss/main.scss";
.hero {
  background-image: linear-gradient(
      90deg,
      rgba(0, 0, 0, 0.4) 0%,
      rgba(0, 0, 0, 0.4) 35%,
      rgba(0, 0, 0, 0.4) 100%
    ),
    url(../assets/img/waterboard.png);
  // height: 50vh;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

.title-spacing {
  padding: 100px 0;
}

.card {
  box-shadow: 0 1rem 1rem rgba(0, 0, 0, 0.4);
  transition: all 0.7s;
  position: relative;
  &:hover {
    background-color: black;
    color: white;
    cursor: pointer;
  }
}

.newsViewAll {
  color: white;
  position: absolute;
  right: 1%;
}
</style>
