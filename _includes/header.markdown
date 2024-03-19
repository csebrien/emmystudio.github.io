        <!--RD Navbar-->
        <div class="rd-navbar-wrap">
          <nav class="rd-navbar rd-navbar-classic" data-layout="rd-navbar-fixed" data-sm-layout="rd-navbar-fixed" data-md-layout="rd-navbar-fixed" data-md-device-layout="rd-navbar-fixed" data-lg-layout="rd-navbar-fixed" data-lg-device-layout="rd-navbar-fixed" data-xl-layout="rd-navbar-static" data-xl-device-layout="rd-navbar-static" data-xxl-device-layout="rd-navbar-static" data-lg-stick-up-offset="46px" data-xl-stick-up-offset="46px" data-xxl-stick-up-offset="46px" data-lg-stick-up="true" data-xl-stick-up="true" data-xxl-stick-up="true">
            <div class="rd-navbar-main-outer">
              <div class="rd-navbar-main">
                <!--RD Navbar Panel-->
                <div class="rd-navbar-panel">
                  <!--RD Navbar Toggle-->
                  <button class="rd-navbar-toggle" data-rd-navbar-toggle=".rd-navbar-nav-wrap"><span></span></button>
                  <!--RD Navbar Brand-->
                  <div class="rd-navbar-brand">
                    <!--Brand--><a class="brand" href="index.html"><img class="brand-logo-dark" src="{{ site.baseurl }}/assets/images/logo-default-138x36.png" alt="" width="138" height="36"/><img class="brand-logo-light" src="{{ site.baseurl }}/assets/images/logo-inverse-138x36.svg" alt="" width="138" height="36"/></a>
                  </div>
                </div>
                <div class="rd-navbar-main-element">
                  <div class="rd-navbar-nav-wrap">
                    <ul class="rd-navbar-nav">
                      <!--li class="rd-nav-item active"><a class="rd-nav-link" href="/">Accueil</a>
                      </li-->
                      <li class="rd-nav-item {% if page.code == "home" %}active{% endif %}"><a class="rd-nav-link" href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.home[page.lang].path }}">Accueil</a>
                      </li>
                      <!--li class="rd-nav-item {% if page.code == "events" %}active{% endif %}"><a class="rd-nav-link" href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.events[page.lang].path }}">Evènements</a>
                      </li-->
                      <li class="rd-nav-item {% if page.code == "services" %}active{% endif %}"><a class="rd-nav-link" href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.work[page.lang].path }}">Prestations</a>
                      </li>
                      <li class="rd-nav-item {% if page.code == "contact" %}active{% endif %}"><a class="rd-nav-link" href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.contact[page.lang].path }}">Contact</a>
                      </li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
          </nav>
        </div>