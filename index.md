--- 
layout: default 
title: Inicio 
---
<div class="page-slideshow" data-animation="fade" data-autoplay="true" data-autoplayspeed="2000" data-speed="550">
	<div class="slick-slide">
	  <div class="page-jumbotron" style="background-image: url(images/home/1-max.jpg); background-size: cover;">
		</div>
	</div>
	<div class="slick-slide">
	  <div class="page-jumbotron" style="background-image: url(images/home/2-max.jpg); background-size: cover;">
		</div>
	</div>
</div>
<main class="main widget-sections">
  <section class="widget-section widget-padded widget_ci-items">
    <div class="widget-wrap" style="background-color: #f9f9f9;">
      <div class="container">
        <div class="row">
          <div class="col-xs-12">
            <h3 class="section-title">CABAÑAS Y HABITACIONES TIPO CHALET</h3>
            <p class="section-subtitle">Ubicada en una zona turística por excelencia.</p>
            <p class="section-subtitle">Todas nuestras Cabañas y Habitaciones tipo Chalet están completamente equipadas y cuentan con estacionamiento privado, servicio de camarera, televisión por cable y una sala de estar.</p>
            <div class="row row-items">
{% for c in site.rooms %}
              <div class="col-lg-4 col-xs-6">
                <div class="item">
                  <figure class="item-thumb">
                    <a href="{{ c.url }}">
														<img src="images/rooms/{{ c.folder }}/{{ c.cover }}-min.jpg" alt="">
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
    <div class="widget-wrap" style="background-color: #054c61">
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
                    {% for index in (3..7) %}
                        <div class="col-lg-4 col-xs-6">
                            <div class="item">
                                <figure class="item-thumb">
                                    <a href="/images/home/{{ index }}-max.jpg" class="ci-lightbox">
                                        <img src="/images/home/{{ index }}-min.jpg" alt="">
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
</main>
