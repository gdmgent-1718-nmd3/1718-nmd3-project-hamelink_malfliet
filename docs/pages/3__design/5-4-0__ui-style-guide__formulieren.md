---
layout   : ui-style-guide
permalink: design/ui-style-guide/formulieren/
published: true
# Custom Page Variables
# ─────────────────────
title: Formulieren
---
<p>Voor heel het project werd enkel een contactformulier gebruikt op onze website.</p>
<p>Verder is ook nog een rating mogelijk in de smartphone-app, evenals checkboxes voor de quizvragen. De rating gebeurt aan de hand van hoedjes (1-5)</p>
<form>
    <div class="form-group">
        <label for="name">Name</label>
        <input type="name" class="form-control" id="name" placeholder="Name">
    </div>
    <div class="form-group">
        <label for="email">Email</label>
        <input type="email" class="form-control" id="email" aria-describedby="emailHelp" placeholder="Email">
    </div>
    <div class="form-group">
        <label for="exampleFormControlTextarea1">Your Message</label>
        <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
    </div>
    <button type="submit" class="btn-custom btn-submit text-uppercase font-weight-bold">Submit</button>
</form>
