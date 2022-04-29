## Приложение по созданию рецептов, которое превращает отдельные кусочки информации (ингредиенты) в законченный продукт (рецепт пиццы).

Приложение разделено на backend (Django) и frontend (Nuxt js).

### активируем виртуальную среду для Django/Python:

notebook:~/recipes_app\$ pipenv shell

### перейдем в директорию с Django:

(recipes_app) notebook:~/recipes_app\$ cd api

### запустим сервер Django:

(recipes_app) notebook:~/recipes_app/api\$ ./manage.py runserver

> Watching for file changes with StatReloader
> Performing system checks...
> Django version 3.1.5, using settings 'api.settings'
> Starting development server at http://127.0.0.1:8000/
> Quit the server with CONTROL-C.

результат можно посмотреть на странице

> http://127.0.0.1:8000/api/recipes/

### перейдем в директорию с Nuxt:

(recipes_app) notebook:~/recipes_app\$ cd client/

### запустим сервер Nuxt:

notebook:~/recipes_app/client\$ npm run dev

> client@1.0.0 dev
> nuxt

> Listening: http://localhost:3000/

### открываем проект в браузере:

http://localhost:3000/
