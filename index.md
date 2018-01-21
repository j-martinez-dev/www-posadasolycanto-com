--- 
layout: default 
title: Home 
---

<div class="page-jumbotron" style="background-image: url(images/home/1.jpg); background-size: cover;">
</div>

<main class="main widget-sections">
  <section class="widget-section">
    <div class="widget-wrap">
      <div class="container">
        <div class="row">
          <div class="col-xs-12">
            <h3 class="section-title">Ubicada en una zona turística por excelencia</h3>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section class="widget-section widget-padded widget_ci-items">
    <div class="widget-wrap" style="background-color: #f9f9f9;">
      <div class="container">
        <div class="row">
          <div class="col-xs-12">
            <h3 class="section-title">CABAÑAS Y HABITACIONES TIPO CHALET</h3>
            <p class="section-subtitle">Todas nuestras Cabañas y Habitaciones tipo Chalet están completamente equipadas y cuentan con estacionamiento privado, servicio de camarera, televisión por cable y una sala de estar.</p>
            <div class="row row-items">
{% for c in site.rooms %}
              <div class="col-lg-4 col-xs-6">
                <div class="item">
                  <figure class="item-thumb">
                    <a href="{{ c.url }}">
														<img src="https://placehold.it/330x395" alt="">
														<p class="item-title">{{ c.title }}</p>
													</a>
                  </figure>
                </div>
              </div>
{% endfor %}
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="widget-section widget-padded widget_ci-hero">
    <div class="widget-wrap" style="background-image: url(https://placehold.it/1920x600/054c61.png);">
      <div class="container">
        <div class="row">
          <div class="col-xs-12">
            <h3 class="section-title">UNA ESTADÍA MÁGICA</h3>
            <p class="section-subtitle">Durante su estadía tendrá la oportunidad de disfrutar del sonido del río que atraviesa nuestra posada y podrá
              observar desde su cabaña una vista única de los paisajes merideños.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="widget-section widget_ci-items">
    <div class="widget-wrap">
      <div class="container">
        <div class="row">
          <div class="col-xs-12">
            <div class="row row-items">
              <div class="col-lg-4 col-xs-6">
                <div class="item">
                  <figure class="item-thumb">
                    <a href="https://placehold.it/1280x1024" class="ci-lightbox">
														<img src="https://placehold.it/330x250" alt="">
													</a>
                  </figure>
                </div>
              </div>
              <div class="col-lg-4 col-xs-6">
                <div class="item">
                  <figure class="item-thumb">
                    <a href="https://placehold.it/1280x1024" class="ci-lightbox">
														<img src="https://placehold.it/330x250" alt="">
													</a>
                  </figure>
                </div>
              </div>
              <div class="col-lg-4 col-xs-6">
                <div class="item">
                  <figure class="item-thumb">
                    <a href="https://placehold.it/1280x1024" class="ci-lightbox">
														<img src="https://placehold.it/330x250" alt="">
													</a>
                  </figure>
                </div>
              </div>
              <div class="col-lg-4 col-xs-6">
                <div class="item">
                  <figure class="item-thumb">
                    <a href="https://placehold.it/1280x1024" class="ci-lightbox">
														<img src="https://placehold.it/330x250" alt="">
													</a>
                  </figure>
                </div>
              </div>
              <div class="col-lg-4 col-xs-6">
                <div class="item">
                  <figure class="item-thumb">
                    <a href="https://placehold.it/1280x1024" class="ci-lightbox">
														<img src="https://placehold.it/330x250" alt="">
													</a>
                  </figure>
                </div>
              </div>
              <div class="col-lg-4 col-xs-6">
                <div class="item">
                  <figure class="item-thumb">
                    <a href="https://placehold.it/1280x1024" class="ci-lightbox">
														<img src="https://placehold.it/330x250" alt="">
													</a>
                  </figure>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</main>