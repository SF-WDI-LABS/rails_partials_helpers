# <img src="https://cloud.githubusercontent.com/assets/7833470/10899314/63829980-8188-11e5-8cdd-4ded5bcb6e36.png" height="60"> Rails Partials & Helpers

**Objective:** Refactor all forms, links, and redirects in this application to take advantage of Rails partials, view helpers (`form_for` and `link_to`), and path prefixes.

## Getting Started

1. Fork this repo, and clone it into your local development folder on your local machine.
2. Change directories into `rails_partials_helpers`, and `bundle install`.
3. Run `rake db:setup` (make sure PosgreSQL is running).
4. Start your Rails server; then you're ready to go!

## Steps to Refactor

1. Find all `<a></a>` tags in the views, and refactor them to use the `link_to` helper. (<a href="http://apidock.com/rails/ActionView/Helpers/UrlHelper/link_to" target="_blank">docs</a>)
1. Find all forms in this application, and refactor them to use the `form_for` helper. (<a href="http://guides.rubyonrails.org/form_helpers.html#binding-a-form-to-an-object" target="_blank">docs</a>)
1. Refactor any duplicate code (hint: recipes new and edit forms) to use a partial. (<a href="http://guides.rubyonrails.org/layouts_and_rendering.html#using-partials" target="_blank">docs</a>)
1. While you're at it, refactor the Bootstrap nav in the application layout to use a partial as well.
1. Find all redirects (`redirect_to`) in the **controller methods**, and refactor them to use path prefixes. (<a href="http://guides.rubyonrails.org/routing.html#prefixing-the-named-route-helpers" target="_blank">docs</a>)

Refer to the [solution branch](/../../tree/solution) for guidance.
