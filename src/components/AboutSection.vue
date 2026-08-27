<template>
  <section class="section novi-background bg-cover section-xl bg-white parallax-scene-js" id="about">
    <div class="container">
      <div class="row row-50 align-items-center justify-content-md-between">
        <div class="col-md-4 col-lg-3">
          <div class="row row-40 row-md-60">
            <div class="col-sm-4 col-md-12 col-xl-11 wow fadeInLeft">
              <article class="box-icon-classic">
                <div class="box-icon-classic-header">
                  <div class="box-icon-classic-icon novi-icon linearicons-apartment"></div>
                  <h6 class="box-icon-classic-title"><a href="#">Desain Arsitektur</a></h6>
                </div>
                <div class="box-icon-classic-text">Layanan perencanaan denah, fasad estetis, dan gambar kerja arsitektur berstandar tinggi.</div>
              </article>
            </div>
            <div class="col-sm-4 col-md-12 col-xl-11 wow fadeInLeft" data-wow-delay=".05s">
              <article class="box-icon-classic">
                <div class="box-icon-classic-header">
                  <div class="box-icon-classic-icon novi-icon linearicons-pen2"></div>
                  <h6 class="box-icon-classic-title"><a href="#">Desain Interior</a></h6>
                </div>
                <div class="box-icon-classic-text">Solusi tata ruang yang elegan, fungsional, dan nyaman dengan furnitur kustom.</div>
              </article>
            </div>
            <div class="col-sm-4 col-md-12 col-xl-11 wow fadeInLeft" data-wow-delay=".1s">
              <article class="box-icon-classic">
                <div class="box-icon-classic-header">
                  <div class="box-icon-classic-icon novi-icon linearicons-lamp"></div>
                  <h6 class="box-icon-classic-title"><a href="#">Desain Tata Cahaya</a></h6>
                </div>
                <div class="box-icon-classic-text">Perpaduan tata lampu artistik dan pencahayaan alami untuk suasana hunian mewah.</div>
              </article>
            </div>
          </div>
        </div>
        <div class="col-md-7 col-lg-6">
          <div class="inset-xl-left-35">
            <h3 class="wow fadeInRight">Hitung Estimasi Biaya<br>Bangunan Anda</h3>
            <h6 class="title-style-1 wow fadeInRight" data-wow-delay=".05s">Tim arsitek kami siap membantu dan merespons kebutuhan Anda</h6>
            <div class="form-style-1 context-dark wow blurIn">
              <!-- RD Mailform-->
              <form class="rd-mailform text-left" data-form-output="form-output-global" data-form-type="contact" method="post" action="bat/rd-mailform.php">
                <div class="form-wrap">
                  <label class="form-label" for="contact-name">Nama Lengkap</label>
                  <input class="form-input" id="contact-name" type="text" name="name" data-constraints="@Required">
                </div>
                <div class="form-wrap">
                  <label class="form-label" for="contact-email">Email Anda</label>
                  <input class="form-input" id="contact-email" type="email" name="email" data-constraints="@Required @Email">
                </div>
                <div class="form-wrap">
                  <label class="form-label" for="contact-phone">Nomor HP / WhatsApp</label>
                  <input class="form-input" id="contact-phone" type="text" name="phone" data-constraints="@Required @PhoneNumber">
                </div>
                <div class="form-button">
                  <button class="button button-jerry button-primary" type="submit">Kirim Konsultasi<span class="button-jerry-line"></span><span class="button-jerry-line"></span><span class="button-jerry-line"></span><span class="button-jerry-line"></span>
                  </button>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="layer-wrap layer-1">
      <div class="layer" data-depth="0.4"><img src="/images/index-7-694x539.png" alt="" width="694" height="539"/>
      </div>
    </div>
  </section>
</template>

<script setup>
</script>

