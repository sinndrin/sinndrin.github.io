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
  <b>sinndrin genossenschaft</b><br>
  c/o Z11 Büro Atelier<br>
  <a href="#" data-reveal-id="addressModal">Zunstrasse 11<br>
  CH-8152 Glattbrugg<br></a>
  <i class="fi-telephone"></i> 044 534 64 54<br>
  <a href="mailto:info@sinndrin.ch"><i class="fi-mail"></i> info@sinndrin.ch</a><br><br>
  MWST-Nr.: CHE-259.799.074 MWST<br>
  <a href="http://zh.powernet.ch/webservices/inet/HRG/HRG.asmx/getHRGHTML?chnr=0205000489&amp;amt=020&amp;toBeModified=0&amp;validOnly=0&amp;lang=1&amp;sort=0"><i class="fi-info"></i> Handelsregistereintrag</a><br>
  <a href="#bankverbindung"><i class="fi-bitcoin-circle"></i> Bankverbindung</a><br><br>

  Wir sind von Montag bis Mittwoch während den üblichen Büroöffnungszeiten am besten erreichbar.
  </p>
  </div>
<!-- BEGIN Team -->
  <div class="large-6 columns">
  <h2 class="show-for-medium-down"><a href="/ueber-uns/team/">Team</a></h2>
  <a href="/ueber-uns/team/">
  {% for post in site.categories.team %}
  <img width=100 src="{{ post.image }}">
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

<a name="bankverbindung"></a>
# Bankverbindung

* IBAN: **CH43 0839 0032 4370 1000 1** <br>

##Daten unserer Bank

* Name: **Alternative Bank Schweiz (ABS)**
* Kontonummer der sinndrin genossenschaft: **324.370.100-01**
* Postkonto: **46-110-7**
* Bankclearing: **8390**
* Swift Code: **ABSOCH22**


<!-- Reveal Modals begin -->
<div id="addressModal" class="reveal-modal" data-reveal>
  <h2>Adresse der sinndrin genossenschaft</h2>

  <p>c/o Z11 Büro Atelier, Zunstrasse 11, CH-8152 Glattbrugg, Schweiz</p>
  <!-- data-interchange begin -->
  <div
      data-interchange="[/ueber-uns/kontakt/default.html, (small)], [/ueber-uns/kontakt/medium.html, (medium)], [/ueber-uns/kontakt/large.html, (large)]">
    <div data-alert class="alert-box secondary radius">
      <!-- default content begin -->
      <!-- TODO: map auf ueber-uns auf google places ändern -->
      <iframe width="280" height="280" frameborder="0" scrolling="no" marginheight="0" marginwidth="0"
              src="https://maps.google.ch/maps?f=q&amp;source=s_q&amp;hl=de&amp;geocode=&amp;q=sinndrin+genossenschaft&amp;aq=&amp;sll=47.377455,8.536715&amp;sspn=0.174132,0.346756&amp;ie=UTF8&amp;hq=sinndrin+genossenschaft&amp;hnear=&amp;t=m&amp;z=12&amp;iwloc=A&amp;cid=16683552561753725560&amp;ll=47.362039,8.533676&amp;output=embed"></iframe><br /><small><a href="https://maps.google.ch/maps?f=q&amp;source=embed&amp;hl=de&amp;geocode=&amp;q=sinndrin+genossenschaft&amp;aq=&amp;sll=47.377455,8.536715&amp;sspn=0.174132,0.346756&amp;ie=UTF8&amp;hq=sinndrin+genossenschaft&amp;hnear=&amp;t=m&amp;z=12&amp;iwloc=A&amp;cid=16683552561753725560&amp;ll=47.362039,8.533676"></iframe>
      <br/>
      <small><a href="https://maps.google.ch/maps?f=q&amp;source=s_q&amp;hl=de&amp;geocode=&amp;q=sinndrin+genossenschaft&amp;aq=&amp;sll=47.377455,8.536715&amp;sspn=0.174132,0.346756&amp;ie=UTF8&amp;hq=sinndrin+genossenschaft&amp;hnear=&amp;t=m&amp;z=12&amp;iwloc=A&amp;cid=16683552561753725560&amp;ll=47.362039,8.533676&amp;output=embed"></iframe><br /><small><a href="https://maps.google.ch/maps?f=q&amp;source=embed&amp;hl=de&amp;geocode=&amp;q=sinndrin+genossenschaft&amp;aq=&amp;sll=47.377455,8.536715&amp;sspn=0.174132,0.346756&amp;ie=UTF8&amp;hq=sinndrin+genossenschaft&amp;hnear=&amp;t=m&amp;z=12&amp;iwloc=A&amp;cid=16683552561753725560&amp;ll=47.362039,8.533676">Grössere Kartenansicht</a></small>
      <!-- default content end -->
    </div>
  </div>
  <!-- data-interchange end -->
  <a class="close-reveal-modal">&#215;</a>
</div>
<!-- Reveal Modals end -->
