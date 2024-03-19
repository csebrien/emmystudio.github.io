---
layout: null
code: contact
title: "Contactez-nous"
permalink: /fr/contactez_nous # change corresponding i18n path variable if permalink changed here!
last_modified_at : "2024-02-18"
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

      <section class="section section-lg bg-default">
        <div class="container">
          <div class="row justify-content-center text-center">
            <div class="col-xxl-6 col-xl-8 col-md-10">
              <h1>Contactez-nous</h1>
              <p class="big px-xxl-4">Prenez contact avec nous et décrivez-nous votre projet, nous reviendrons vers vous avec une offre adaptée</p>
            </div>
          </div>
          <div class="row row-40 justify-content-center">
            <div class="col-xl-5 col-md-6"><img src="{{ site.baseurl }}/assets/images/contacts-01-570x670.jpg" alt="" width="570" height="670"/>
            </div>
            <div class="col-xl-5 col-md-6">
              <h2>Restons en contact</h2>
              <p>Nos equipes s'efforceront de prendre en contact avec vous rapidement.</p>
              <!--RD Mailform-->
              <form class="rd-form rd-mailform" data-form-output="form-output-global" data-form-type="contact" method="post" action="https://formspree.io/f/xnqebadz" id="contact-form">
			 	<input type="text" name="_gotcha" style="display:none" />
				<input name="subject" value="Nouveau message du site emmystudio!" style="display:none"/>
				<input type="hidden" id="g-recaptcha-response" name="g-recaptcha-response">
				<div class="response"></div>
                <div class="form-wrap">
                  <input class="form-input" id="contact-form-name" type="text" name="name" data-constraints="@Required">
                  <label class="form-label" for="contact-form-name">Nom</label>
                </div>
                <div class="form-wrap">
                  <input class="form-input" id="contact-form-phone" type="text" name="phone" data-constraints="@Numeric">
                  <label class="form-label" for="contact-form-phone">Téléphone</label>
                </div>
                <div class="form-wrap">
                  <input class="form-input" id="contact-form-email" type="email" name="email" data-constraints="@Email @Required">
                  <label class="form-label" for="contact-form-email">Email</label>
                </div>
                <div class="form-wrap">
                  <label class="form-label" for="contact-form-message">Votre message</label>
                  <textarea class="form-input" id="contact-form-message" name="message" data-constraints="@Required"></textarea>
                </div>
                <button class="btn" type="submit">Envoyer</button>
              </form>

            </div>
          </div>
        </div>
      </section>

	 <footer class="section footer-great bg-default">
        <div class="container">
          <div class="row row-40 justify-content-center">
            <div class="col-xl-5 col-sm-6">
              <p class="big">Restons en contact</p>
              <div class="tel-link"><a href="tel:0663271829">+33 (6) 63 27 18 29</a></div>
              <p><a href="#">12 avenue Andrée 94100 Saint-Maur-Des-Fossés</a></p>
              <p><a href="mailto:contact@emmystudio.com">contact@emmystudio.com</a></p>
              <ul class="footer-list">
                <li class="footer-list-item"><a rel='nofollow' target="_blank" href="https://www.instagram.com/emmy_studio_floral_design"><img src="{{ site.baseurl }}/assets/images/instagram.png" width="45"  style='border-width:0px;' /></a></li>
				        <li class="footer-list-item"><a rel='nofollow' target="_blank" href='https://www.mariages.net' title='Mariages.net'><img alt='Mariages.net' src='https://www.mariages.net/images/sellos/label-partenaire--pp342822.png' style='border-width:0px;' /></a></li>
              </ul>
              <p class="rights"><span>&copy;&nbsp;</span><span class="copyright-year"></span><span>.&nbsp;</span><span>Tous droits réservés.&nbsp;</span>
              <a href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.legal[page.lang].path }}">{{ site.data.i18n.footer[page.lang].legal }}</a>
              <a href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.cgv[page.lang].path }}">{{ site.data.i18n.footer[page.lang].cgv }}</a></p>
            </div>
            <div class="col-xl-5 col-sm-6 text-sm-center"><img src="{{ site.baseurl }}/assets/images/contacts-02-420x494.jpg" alt="" width="420" height="494"/>
            </div>
          </div>
        </div>
      </footer>

	</div><!--wrapper end-->

	<div class="snackbars" id="form-output-global"></div>
{% include scripts.markdown %}
<script src="https://www.google.com/recaptcha/api.js?render=6LdC5FcjAAAAABzm0IjJdAbPZfKkwHi0e6FzgtDT"></script>
<script>
	grecaptcha.ready(function () {
		grecaptcha.execute('6LdC5FcjAAAAABzm0IjJdAbPZfKkwHi0e6FzgtDT', {action: 'submit'}).then(function (token) {
			document.getElementById('g-recaptcha-response').value = token;
		});
	});
</script>

</body>

</html>
