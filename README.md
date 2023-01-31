# my_module
Project > urls.py

from properties.routers import router
urlpatterns = [
    path('actionProperty',include(router.urls)),
]

