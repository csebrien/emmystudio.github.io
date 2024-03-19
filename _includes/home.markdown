<html class="wide wow-animation" lang="fr">
{% include head.markdown %}

<body>
	
	{% include page-loading.markdown %}

	<div class="page">
			
		<header class="section page-header">
			{% include header.markdown %}
		</header><!--header end-->

		<!-- Intro-->
      <section class="section pt-5 pt-lg-0">
        <div class="container">
          <div class="row row-40 align-items-end">
            <div class="col-lg-6">
              <figure class="intro-figure"><img src="{{ site.baseurl }}/assets/images/home-01-945x820.jpg" alt="" width="945" height="820"/>
              </figure>
            </div>
            <div class="col-xxl-4 col-lg-6 mx-xl-auto">
              <div class="intro-content">
                <p class="big">Harmonie et émotion !</p>
                <h1>Design floral<br/>et décoration</h1>
                <p class="big">Bouquets – évènements - Set design et ateliers<br/>à {{ page.town }}</p>
                <a class="btn" href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.contact[page.lang].path }}">Décrivez-nous votre projet</a>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- Why us-->
      <section class="section section-lg bg-default">
        <div class="container">
          <div class="row row-40 justify-content-xxl-center justify-content-between align-items-center">
            <div class="col-xl-5 col-lg-6">
              <p class="big">Nos Valeurs</p>
             
              <ul class="list-lg">
                <li>
                  <p>Pour chaque occasion spéciale, nous puisons dans notre créativité et notre expertise pour concevoir des décors floraux qui captivent les regards et touchent les cœurs. Chaque bouquet est soigneusement composé, chaque arrangement est méticuleusement orchestré, afin de créer une ambiance magique et unique, en parfaite harmonie avec vos envies et vos besoins.</p>
                </li>
                <li>
                  <p>Que vous rêviez d'une cérémonie intimiste, d'une réception grandiose ou d'un événement d'entreprise impressionnant, nous mettons tout en œuvre pour réaliser vos souhaits les plus précieux. Avec Emmy Studio, chaque moment devient une œuvre d'art florale, où la beauté et l'élégance se conjuguent pour créer des souvenirs éternels.</p>
                </li>
              </ul>
            </div>
            <div class="col-xxl-5 col-lg-6">
              <div class="image-group-1"><img src="{{ site.baseurl }}/assets/images/home-02-420x440.jpg" alt="" width="420" height="440"/><img src="{{ site.baseurl }}/assets/images/home-03-420x615.jpg" alt="" width="420" height="615"/>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- Events-->
      <section class="section section-lg bg-default">
        <div class="container">
          <div class="row row-40 align-items-center">
            <div class="col-lg-6">
              <figure class="intro-figure"><img src="{{ site.baseurl }}/assets/images/home-08-945x730.jpg" alt="" width="945" height="730"/>
              </figure>
            </div>
            <div class="col-xxl-4 col-lg-6 mx-xl-auto">
              <h2>Nos Evènements</h2>
                    <div class="event">
                      <p class="event-text">Contactez-nous afin d'être informé lors de nouveaux événements!</p>
                    </div>
                    <a class="btn" href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.contact[page.lang].path }}">Contactez-nous</a>
            </div>
          </div>
        </div>
      </section>
      

		<footer class="section footer-classic bg-gray-100 text-center">
			{% include footer.markdown %}
		</footer><!--footer end-->

	</div><!--wrapper end-->

	<div class="snackbars" id="form-output-global"></div>
{% include scripts.markdown %}


</body>

</html>
