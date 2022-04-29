# Tour Of Heroes API

Ruby on Rails 7  course as an API creating a Heroes CRUD.

This repository is part of the [Curso de Ruby on Rails 6 como API](https://www.youtube.com/watch?v=gTR6lx00Nac&list=PLqsayW8DhUmuvgOX08aXYk6Y-HGrdYg20) on YouTube.

<table>
  <tr>
    <td>Ruby version</td>
    <td>
      3.1.2
    </td>
  </tr>
  <tr>
    <td>Rails version</td>
    <td>
      7.0.2.x
    </td>
  </tr>
  <tr>
    <td>Database</td>
    <td>
      SQLite3 (dev) / PostgreSQL (prod)
    </td>
  </tr>
</table>

## Initial settings to run the project

```bash
# clone the project
git clone https://github.com/diogeneshas/curso_tour_of_heroes_api.git

# enter the cloned directory
cd curso_tour_of_heroes_api

# install Ruby on Rails dependencies
bundle install --without production

# create the development and test databases
rails db:create

# create the tables
rails db:migrate

# run the project
rails s