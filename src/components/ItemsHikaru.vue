<template>
  <!-- Women Banner Section Begin -->
  <section class="women-banner spad">
    <div class="container-fluid">
      <div class="row">
        <div class="col-lg-12 mt-5">
          <carousel
            class="product-slider"
            :item="3"
            :nav="false"
            :autoplay="true"
            :dots="false"
          >
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/baju-nabila.jpg" alt="" />
                <ul>
                  <li class="w-icon active">
                    <a href="#"><i class="icon_bag_alt"></i></a>
                  </li>
                  <li class="quick-view">
                    <router-link to="/product">+ Quick View
                    </router-link>
                  </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Batik Muslim</div>
                <router-link to="/product">
                  <a href="#">
                    <h5>Magenta Narrow</h5>
                  </a>
                </router-link>
                <div class="product-price">
                  Rp 560.000
                  <span>Rp 850.000</span>
                </div>
              </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/uniform.png" alt="" />
                <ul>
                  <li class="w-icon active">
                    <a href="#"><i class="icon_bag_alt"></i></a>
                  </li>
                  <li class="quick-view"><a href="#">+ Quick View</a></li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Seragam Sekolah</div>
                <a href="#">
                  <h5>Asian Uniform</h5>
                </a>
                <div class="product-price">Rp 200.000</div>
              </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/products/women-3.jpg" alt="" />
                <ul>
                  <li class="w-icon active">
                    <a href="#"><i class="icon_bag_alt"></i></a>
                  </li>
                  <li class="quick-view"><a href="#">+ Quick View</a></li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Towel</div>
                <a href="#">
                  <h5>Pure Pineapple</h5>
                </a>
                <div class="product-price">$34.00</div>
              </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/products/women-4.jpg" alt="" />
                <ul>
                  <li class="w-icon active">
                    <a href="#"><i class="icon_bag_alt"></i></a>
                  </li>
                  <li class="quick-view"><a href="#">+ Quick View</a></li>
                  <li class="w-icon">
                    <a href="#"><i class="fa fa-random"></i></a>
                  </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Towel</div>
                <a href="#">
                  <h5>Converse Shoes</h5>
                </a>
                <div class="product-price">$34.00</div>
              </div>
            </div>
          </carousel>
        </div>
      </div>
    </div>
  </section>
  <!-- Women Banner Section End -->
</template>

<script>
import carousel from "vue-owl-carousel";
export default {
  name: "ItemsHikaru",
  components: { carousel },
};
</script>
<style scoped>
.product-item {
  margin-right: 25px;
}
</style>