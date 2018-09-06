---
layout: default
title: "Contact met PolderPrinses"
---

<div id="contact">
  <h1 class="pageTitle">Contact ...</h1>
  <div class="contactContent">
    <p class="intro">Neem contact op met PolderPrinses</p>

    <p>Gebruik het formulier om een reactie te geven, een gedicht 'op maat' aan te vragen, een bericht te sturen of om zo maar iets achter te laten.</p>

    <p>Ben je geraakt door een gedicht en wil je dit publiceren, dan graag vooraf een bericht sturen. Hartelijk dank!</p>
  </div>

  <form action="http://formspree.io/daniela@polderprinses.nl" method="POST">
    <input type="hidden" name="_format" value="plain">
    <input type="hidden" name="_subject" value="Website contact!">
    <input type="hidden" name="_next" value="http://polderprinses.nl/bedankt/">
    <input type="hidden" name="_language" value="nl">
    <input type="text" name="_gotcha" style="display:none">
    <label for="name">Naam</label>
    <input type="text" id="name" name="name" class="full-width"><br>
    <label for="email">Emailadres</label>
    <input type="email" id="email" name="_replyto" class="full-width"><br>
    <label for="message">Boodschap</label>
    <textarea name="message" id="message" cols="30" rows="10" class="full-width"></textarea><br>
    <input type="submit" value="Verstuur" class="button">
  </form>
</div>
