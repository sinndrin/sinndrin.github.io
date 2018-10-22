---
layout: two-columns
title:  "Kontakt"
---
<!-- BEGIN script loading -->
<!-- BEGIN facebook -->
<div id="fb-root"></div>
<script>(function(d, s, id) {
  var js, fjs = d.getElementsByTagName(s)[0];
  if (d.getElementById(id)) return;
  js = d.createElement(s); js.id = id;
  js.src = "//connect.facebook.net/de_DE/sdk.js#xfbml=1&version=v2.0";
  fjs.parentNode.insertBefore(js, fjs);
}(document, 'script', 'facebook-jssdk'));</script>
<!-- END facebook -->
<!-- END script loading -->

<!-- BEGIN Kontakt -->
<div class="row">
  <div class=" large-6 columns">
  <p>
  <b>Reparaturadresse</b><br>
  sinndrin genossenschaft<br>
  Bahnstrasse 17<br>
  CH-8400 Winterthur<br></a>
  <b>Korrespondenzadresse</b><br>
  sinndrin genossenschaft<br>
  Zürcherstrasse 54<br>
  CH-5432 Neuenho<br></a>
  <a href="mailto:info@sinndrin.ch"><i class="fi-mail"></i> info@sinndrin.ch</a><br>
  <a href="/ueber-uns/spieleabend/"><i class="fi-puzzle"></i> Persönliches Kennenlernen an einem unserer Spieleabende</a><br><br>
  <b>Fairphone Support:</b><br><a href="https://support.sinndrin.org/de"><i class="fi-page-multiple"></i> Fairphone Support Seite</a><br><a href="mailto:support@sinndrin.ch"><i class="fi-mail"></i> support@sinndrin.ch</a><br><br>
  MWST-Nr.: CHE-259.799.074 MWST<br>
  <a href="http://zh.powernet.ch/webservices/inet/HRG/HRG.asmx/getHRGHTML?chnr=0205000489&amp;amt=020&amp;toBeModified=0&amp;validOnly=0&amp;lang=1&amp;sort=0"><i class="fi-info"></i> Handelsregistereintrag</a><br>
  <a href="#bankverbindung"><i class="fi-bitcoin-circle"></i> Bankverbindung</a><br><br>

  Wir sind am Montag, Mittwoch und Freitag während den üblichen Büroöffnungszeiten am besten erreichbar.
  </p>
  </div>
<!-- BEGIN Team -->
  <div class="large-6 columns">
  <h2 class="show-for-medium-down"><a href="/ueber-uns/team/">Team</a></h2>
  <a href="/ueber-uns/team/">
  {% for post in site.categories.team %}
  <img alt="{{ post.title }}" width="100" src="{{ post.image }}">
  {% endfor %}
  </a>
  </div>
<!-- END Team -->
  </div>
<!-- END Kontakt -->


<!-- BEGIN Social Profiles -->
<div class="row">
  <div class="columns">
    <h2>Soziale Netzwerke</h2>
  </div>
</div>

<div class="row">
  <!-- BEGIN Facebook -->
  <div class="large-6 columns">
    <h3><a style="color:#3b5998;" href="https://www.facebook.com/sinndrin" target="_blank" rel="sinndrin genossenschaft"><i class="fi-social-facebook"></i> Facebook</a></h3>
    <div class="fb-like-box" data-href="https://www.facebook.com/sinndrin" data-colorscheme="light" data-show-faces="true" data-header="true" data-stream="false" data-show-border="false"></div>
  </div>
  <!-- END Facebook -->

  <!-- BEGIN Google+ -->
  <div class="large-6 columns">
    <h3><a style="color: red;" href="https://plus.google.com/+sinndringenossenschaftZürich" target="_blank" rel="sinndrin genossenschaft"><i class="fi-social-google-plus"></i> Google+</a></h3>
    <!-- BEGIN Google+ Code -->
    <script type="text/javascript" src="https://apis.google.com/js/plusone.js"></script>
    <g:page href="https://plus.google.com/+sinndringenossenschaftZürich"></g:page>
    <!-- END Google+ Code -->
  </div>
  <!-- END Google+ -->
</div>

<!-- TODO: ugly spacing -->
<br><br>

<div class="row">
<!-- BEGIN Twitter -->
<div class="large-6 columns">
<h3><a style="color:#55acee;" href="https://twitter.com/sinndrin" target="_blank" rel="sinndrin genossenschaft"><i class="fi-social-twitter"></i> Twitter</a></h3>
<!-- BEGIN Twitter Code -->
<a class="twitter-timeline"  href="https://twitter.com/sinndrin"  data-widget-id="502772720589746176">Tweets von @sinndrin</a>
    <script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+"://platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>


<!-- >END Twitter Code -->
</div>
<!-- END Twitter -->

<!-- BEGIN Weitere -->
<div class="large-6 columns">
<h3>Weitere Profile</h3>

<ul>
  <!-- BEGIN XING -->
  <li><h4><a style="color: green;" href="https://www.xing.com/companies/sinndringenossenschaft" target="_blank" rel="sinndrin genossenschaft">Xing</a></h4></li>
  <!-- >END XING -->
  <!-- BEGIN Github -->
  <li><h4><a style="color:#222;" href="https://github.com/sinndrin" target="_blank" rel="sinndrin genossenschaft"><i class="fi-social-github"></i> GitHub</a></h4></li>
   <!-- >END Github -->
  </ul>
</div>
<!-- END Weitere -->
</div>

# <a name="bankverbindung"></a> Bankverbindung

* IBAN: **CH43 0839 0032 4370 1000 1** <br>

## Daten unserer Bank

* Name: **Alternative Bank Schweiz (ABS)**
* Kontonummer der sinndrin genossenschaft: **324.370.100-01**
* Postkonto: **46-110-7**
* Bankclearing: **8390**
* Swift Code: **ABSOCH22**
