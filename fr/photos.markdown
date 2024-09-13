---
layout: null
code: photos
title: "Photos"
permalink: /fr/photos # change corresponding i18n path variable if permalink changed here!
last_modified_at : "2024-09-13"
---
{::nomarkdown}
<!DOCTYPE html>
{:/nomarkdown}
<html class="wide wow-animation" lang="fr">
{% include head.markdown %}

<body>
	
	{% include page-loading.markdown %}

	<div class="page">
			
		<header class="section page-header">
			{% include header.markdown %}
		</header><!--header end-->

		<!-- Post-->
      <section class="section section-lg bg-default">
        <div class="container">
          <div class="row row-40 justify-content-center">
           
            <div class="col-6">
              <a class="link-image" href="{{ site.baseurl }}/{{ page.lang }}/accessories"><img src="{{ site.baseurl }}/assets/images/accessoires/principale-ACC.jpg" alt="" width="570" height="760"/></a>
              <h4>Accessoires</h4>
            </div>
            <div class="col-6">
              <a class="link-image" href="{{ site.baseurl }}/{{ page.lang }}/bouquets-et-boutonnieres"><img src="{{ site.baseurl }}/assets/images/bouquets-boutonnieres/principale-B.jpg" alt="" width="570" height="760"/></a>
              <h4>Bouquets et boutonnières</h4>
            </div>
          </div><!-- row -->

          <div class="row row-40 justify-content-center">
           
            <div class="col-6">
              <a class="link-image" href="{{ site.baseurl }}/{{ page.lang }}/centres-table"><img src="{{ site.baseurl }}/assets/images/centres-de-table/principale-CENTRE.jpg" alt="" width="570" height="760"/></a>
              <h4>Centres de table</h4>
            </div>
            <div class="col-6">
              <a class="link-image" href="{{ site.baseurl }}/{{ page.lang }}/decors"><img src="{{ site.baseurl }}/assets/images/decors/principale-decor.jpg" alt="" width="570" height="760"/></a>
              <h4>Décors</h4>
            </div>
          </div><!-- row -->

          <div class="row row-40 justify-content-center">
           
            <div class="col-6">
              <a class="link-image" href="{{ site.baseurl }}/{{ page.lang }}/vehicules"><img src="{{ site.baseurl }}/assets/images/vehicules/principale-vehicule.jpg" alt="" width="570" height="760"/></a>
              <h4>Véhicules</h4>
            </div>
          </div><!-- row -->

        </div><!-- container -->
      </section>

		<footer class="section footer-classic bg-gray-100 text-center">
			{% include footer.markdown %}
		</footer><!--footer end-->

	</div><!--wrapper end-->

	<div class="snackbars" id="form-output-global"></div>
{% include scripts.markdown %}


</body>

</html>
