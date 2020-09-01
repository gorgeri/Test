# Fullstack Developer Test Task

Need to create admin panel to manage companies. Basically, project to manage companies and their
employees. Mini-CRM.

Requirements:
* API Laravel Auth: ability to log in as administrator
* Use database seeds to create first user with email admin@admin.com and password “password”, and
use "Faker" to create 10 000 Companies & 10 000 Employees
* CRUD functionality (Create / Read / Update / Delete) for two menu items:Companies and Employees.
* Companies DB table consists of these fields: Name (required), email, logo (minimum 100×100), website
* Employees DB table consists of these fields: First name (required), last name (required), Company
(foreign key to Companies), email, phone
* Use database migrations to create those schemas above
* Store companies logos in storage/app/public folder and make them accessible from public
* Use basic Laravel resource controllers with default methods – index, create, store etc.
* Use Laravel’s validation function, using FormRequest classes
* Use Laravel’s pagination for showing Companies/Employees list, 10 entries per page
* Email notification: send email whenever new company is entered (use Mailgun or Mailtrap)
* Make the project multi-language (using resources/lang folder)
* [ ] Use CSS Framework (Material Design Vue.js, Materialize etc)
* [ ] All front-end should be realised like SPA with using VueJS / Vuex.
