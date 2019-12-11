{% load static %}
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <title>{% block title %}Title{% endblock title %}</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
    {% block stylesheet %}{% endblock stylesheet %}
  </head>
  <body>
    <main>
    {% block content %}
    {% endblock content %}
    </main>
    <script src="https://code.jquery.com/jquery-3.1.0.min.js"></script>
    <script src='https://code.jquery.com/jquery-3.2.1.min.js'></script>
    <script src='https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js'></script>
    {% block javascript %}
    {% endblock javascript%}
  </body>
</html>
