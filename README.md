# Desafioblog

Blog basico

## Description

Proyecto en rails para estudiantes de Desafio Latam.

## Badges

Images that convey metadata, for example if all the tests are passing or not in the project.

## Visuals

Screenshots, videos or GIFs of the project.

## Starting 🚀

Instructions to obtain a copy of the project and implement it on a local machine for development and testing.

### Pre-requisites 📋

Dependencies to run the project:

- Windows, linux, Mac  all versions.
- Ruby Ver. 3.1.2 or higher.
- Ruby on Rails Ver. 7.0.3
- Database development envirionment Sqlite3.
- Database production envirionment Postgresql.

### Installation 🔧

1. Crear proyecto en rails.

```bash
rails new desafioblog
```

2. Entrar al proyecto.

```bash
cd desafioblog
```

3. Verificar que el proyecto se ha creado correctamente.

```bash
rails server
```

4. Crear migracion posts con los campos necesarios.

```bash
rails g migration posts title image_url content:text
```

5. Crear modelo Post.

```bash
rails g model Post
```

6. Correr migraciones para la base de datos.

```bash
rails db:migrate
```

7. Crear controlador PostsController.

```bash
rails g controller Posts index new
```

8. Establecer ruta raiz del proyecto. Ir al archivo routes.rb y agregar la siguiente linea:

```bash
root 'posts#index'
```

Nota: Se recomienda cambiar todos los get a posts controller por "resources :posts"

9. Ir al controlador pages y agregar las lineas que se encuntren en el archivo pages_controller.rb de este proyecto.

10. ir al modelo Post y agregar las lineas que se encuntren en el archivo post.rb de este proyecto.

11. Crear vista _form.html.erb en la carpeta posts.

12. Reemplazar el contenido de la vista _form.html.erb por el siguiente:

13. Reemplazar el contenido de la vista index.html.erb por el siguiente:

14. Reeplazar el contenido de la vista new.html.erb por el siguiente:

15. ir al archivo gemfile y reemplazar la gema sqlite por la siguinte linea:

```bash
gem 'sqlite3', group: :development
gem 'pg', group: :production
```
16. Crear un proyecto en heroku.

```bash
heroku create
```

17. hacer un push a heroku.

```bash
git push heroku main
```

18. Hacer una migracion con heroku

```bash
heroku run rails db:migrate
```

## Running the tests ⚙️

Description of how to run the tests:

```bash
give an example
```

### Analyze end-to-end tests 🔩

Explain the reasons for the tests, what they verify and how to interpret the results

### Coding style tests ⌨️

Description of style tests

```bash
give an example
```

## Deployment 📦

Description of how to bring the project to production

## Built with 🛠️

Tools used to create the project

- [Ruby](https://www.ruby-lang.org/en/) - Programming language used
- [Ruby on Rails](https://rubyonrails.org) - The web framework used
- [Ruby gems](https://rubygems.org) - Dependency manager
- [Postgresql](https://www.postgresql.org) - Database
- [Bulma IO](https://bulma.io) - Css Framework

## Contribute 🖇️

Please read [CONTRIBUTING.md](https://gist.github.com/brayandiazc/xxxxxx) for details of our code of conduct, and the process for submitting pull requests.

## Wiki 📖

Find more information on how to use it in [Wiki](https://github.com/your/project/wiki)

## Medium

Ways to get help:

- Forum
- Email
- Group

## Roadmap

Ideas for future versions.

## Versioning 📌

Version control system [Git](https://git-scm.com).
For all available versions, check out the [tags in this repository](https://github.com/tu/proyecto/tags).

## Authors ✒️

People who have contributed to the project:

- **Brayan DIaz C** - _Initial Work_ - [brayandiazc](https://github.com/brayandiazc)
- **Gloria Salcedo** - \* Documentation

You can also look at the list of all [contributors](https://github.com/your/project/contributors) who have participated in this project.

## License 📄

This project is under the License (Your License) - see the file [LICENSE.md] (LICENSE.md) for details

## Expressions of Gratitude 🎁

This readme file is developed using as reference the following projects:

- [README-español.md](https://gist.github.com/Villanuevand/6386899f70346d4580c723232524d35a) - created by [Andrés Villanueva](https://gist.github.com/Villanuevand)
- [Make a README](https://www.makeareadme.com) - created by [Danny Guo](https://github.com/dguo)
- Invite a beer 🍺 or a coffee ☕ to someone on the team.
- Give thanks publicly 🤓.
- etc.

---

⌨️ with ❤️ by [Brayan Diaz C](https://github.com/brayandiazc) 😊