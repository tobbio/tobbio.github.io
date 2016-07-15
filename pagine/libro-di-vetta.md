---
layout: archive
title: Libro di vetta
permalink: /libro-di-vetta/ 
share: false
--- 

Una sicuramente meno affascinante alternativa alla versione cartacea presente nel bivacco…  
Potete "firmare" o inviare un vostro racconto compilando il form [qui](#form)

<div class="tiles">
{% for post in site.categories.libro-di-vetta%}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

<a id="form"></a> 
## Scrivi 
<form action="https://getsimpleform.com/messages?form_api_token=f11a9e6dbe5ef1d546bcc99796912267" method="post"> <!-- the redirect_to is optional, the form will redirect to the referrer on submission --> <input type='hidden' name='redirect_to' value='<the complete return url e.g. http://fooey.com/thank-you.html>' /> <!-- all your input fields here.... --> <textarea name="content"></textarea><input type='submit' value='Test form' /> </form>
