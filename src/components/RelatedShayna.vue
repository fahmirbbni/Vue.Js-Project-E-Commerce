<template>
  <!-- Related Products Section End -->
  <section class="related-product"> 
    <carousel class="products-item" :items="1" :nav="false" :autoplay="true">

  <div class="related-products spad">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <div class="section-title">
            <h2>Related Products</h2>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-3 col-sm-6">
          <div class="product-item">
            <div class="pi-pic">
              <img src="img/R2.png" alt />
              <ul>
                <li class="w-icon active">
                  <a href="#">
                    <i class="icon_bag_alt"></i>
                  </a>
                </li>
                <li class="quick-view">
                  <router-link to="/product">+ Quick View</router-link>
                </li>
              </ul>
            </div>
            <div class="pi-text">
              <div class="catagory-name">Toys</div>
              <a href="#">
                <h5>Luffy</h5>
              </a>
              <div class="product-price">
                $14.00
                <span>$35.00</span>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-sm-6">
          <div class="product-item">
            <div class="pi-pic">
              <img src="img/R3.png" alt />
              <ul>
                <li class="w-icon active">
                  <a href="#">
                    <i class="icon_bag_alt"></i>
                  </a>
                </li>
                <li class="quick-view">
                  <a href="#">+ Quick View</a>
                </li>
              </ul>
            </div>
            <div class="pi-text">
              <div class="catagory-name">Toys</div>
              <a href="#">
                <h5>Ace</h5>
              </a>
              <div class="product-price">$13.00</div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-sm-6">
          <div class="product-item">
            <div class="pi-pic">
              <img src="img/R4.png" alt />
              <ul>
                <li class="w-icon active">
                  <a href="#">
                    <i class="icon_bag_alt"></i>
                  </a>
                </li>
                <li class="quick-view">
                  <a href="#">+ Quick View</a>
                </li>
              </ul>
            </div>
            <div class="pi-text">
              <div class="catagory-name">Toys</div>
              <a href="#">
                <h5>Sanji</h5>
              </a>
              <div class="product-price">$34.00</div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-sm-6">
          <div class="product-item">
            <div class="pi-pic">
              <img src="img/R1.png" alt />
              <ul>
                <li class="w-icon active">
                  <a href="#">
                    <i class="icon_bag_alt"></i>
                  </a>
                </li>
                <li class="quick-view">
                  <a href="#">+ Quick View</a>
                </li>
              </ul>
            </div>
            <div class="pi-text">
              <div class="catagory-name">Toys</div>
              <a href="#">
                <h5>Zoro</h5>
              </a>
              <div class="product-price">$34.00</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

    </carousel>
  </section>
  <!-- Related Products Section End -->
</template>

<script>
import carousel from "vue-owl-carousel";

export default {
    name: "RelatedShayna",
    component: {carousel}
}
</script>