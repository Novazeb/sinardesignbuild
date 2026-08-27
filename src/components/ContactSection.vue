<template>
  <section class="section novi-background bg-cover bg-white section-inset-1 parallax-scene-js">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-6 d-none d-lg-block wow fadeInLeft">
          <img src="/images/index-6-538x694.png" alt="" width="538" height="694"/>
        </div>
        <div class="col-md-8 col-lg-6">
          <div class="inset-xl-left-35 section-sm">
            <h3 class="wow fadeInRight">Konsultasikan Proyek<br>Bersama Tim Kami</h3>
            <h6 class="title-style-1 wow fadeInRight" data-wow-delay=".05s">Mari Wujudkan Bangunan Impian Anda Bersama Kami</h6>
            <div class="form-style-1 context-dark wow blurIn">
              <!-- RD Mailform-->
              <form class="rd-mailform text-left" data-form-output="form-output-global" data-form-type="contact" method="post" action="bat/rd-mailform.php">
                <div class="form-wrap">
                  <label class="form-label" for="contact-name-2">Nama Lengkap</label>
                  <input class="form-input" id="contact-name-2" type="text" name="name" data-constraints="@Required">
                </div>
                <div class="form-wrap">
                  <label class="form-label" for="contact-email-2">Alamat Email</label>
                  <input class="form-input" id="contact-email-2" type="email" name="email" data-constraints="@Required @Email">
                </div>
                <div class="form-wrap">
                  <label class="form-label" for="contact-phone-2">Nomor HP / WhatsApp</label>
                  <input class="form-input" id="contact-phone-2" type="text" name="phone" data-constraints="@Required @PhoneNumber">
                </div>
                <div class="form-button">
                  <button class="button button-jerry button-primary" type="submit">
                    Kirim Pesan
                    <span class="button-jerry-line"></span>
                    <span class="button-jerry-line"></span>
                    <span class="button-jerry-line"></span>
                    <span class="button-jerry-line"></span>
                  </button>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="layer-wrap layer-3">
      <div class="layer" data-depth="0.4">
        <img src="/images/index-9-1047x531.png" alt="" width="1047" height="531"/>
      </div>
    </div>
  </section>
</template>

<script setup>
</script>

