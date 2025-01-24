# Websocketit ja Django

Esimerkkiprojekti websocket-ominaisuuksien tuomisesta Django-projektiin.

### Asennus
- ```pip install -r requirements.txt```

### Käynnistys
- ```cd testproject```
- ```python manage.py migrate```
- ```python manage.py runserver```
- Avaa [localhost:8000/chat](http://localhost:8000/chat/)

### Muuta
Käytössä [Daphne-palvelin](https://github.com/django/daphne) sekä [Django-kanavat](https://github.com/django/channels).

Ks. myös [geeksforgeeks.org](https://www.geeksforgeeks.org/django-channels-introduction-and-basic-setup/), [medium.com](https://medium.com/@adabur/introduction-to-django-channels-and-websockets-cb38cd015e29), [channels.readthedocs.io](https://channels.readthedocs.io/en/latest/topics/consumers.html)

