# React with TS and Sass Folder
This is a template repo to start on a new react sass project

## Folder structures
### view raw to see it well

React Setup Folder Structure

React

src/
|- assets/ (apply to all project, the binaries)
|  |-brand/
|  |- images/
|  |- svg/
|
|-common/ (apply to all project)
|
|-pages/ (folder for each page of application, apply to all project)
| |- PageOne/
| |- PageTwo/
| |- PageThree/
| |  |-- components/
| |  |   |- ComponentName/
| |  |   |-index.test.ts
| |  |   |-index.tsx (use .tsx instead of .ts because they are components)
|
| |  |-hooks/
| |  |-HookUseName/ (eg. this is for graphql's query.gpl)
| |  |-f index.tsx
|
| |-f models.ts (for whole page. for interfaces eg. data models. reuseable throughout components)
| |-f style.css (for whole page.)
| |-f util.ts (for whole page. for reuseable functions)
|
|-setup/ (apply to all project, about setting up the whole application)
| |-app-context-manager/
| |-auth/ (to be consumed by app-context-manager)
| |-routes-manager/
| |-f index.tsx (declare react router dom routes)
|
|-store/ (for redux)
| |-actions/
| |-reducers/
|
|- styles/
|  |- MyAppScss.scss
|
|-f app.css (styles for the whole project)
|-f app.ts
|-f index.ts

Note:
Use absolute paths for imports




sass

sass/
|
|– base/
|   |– _base.scss
|   |– _reset.scss
|   |– _typography.scss
|   |– _normalize.scss
|
|– layout/
|   |– _navbar.scss
|   |– _footer.scss
|   |– _sidebar.scss
|   |– _header.scss
|
|– abstracts/
|   |– _variables.scss
|   |– _colors.scss
|   |– _mixins.scss
|
|– components/
|   |– _alert.scss
|   |– _button.scss
|   |– _label.scss
|   |– _modal.scss
|   |– _course-card.scss
|   |– _infobox.scss
|   |– _success-popup.scss
|   |– _profile-card.scss
|
|– pages/
|   |– _product.scss
|   |– _product-single.scss
|   |– _blog.scss
|   |– _blog-single.scss
|   |– _invoice.scss
|   |– _login.scss
|   |– _signup.scss
|
|– themes/
|   |– _dark-theme.scss
|   |– _light-theme.scss
|   |– _material-theme.scss
|   |– _flat-theme.scss
|
|– vendors/
|   |– _bootstrap.scss
|   |– _owl-carousel.scss
|   |– _jqueryui.scss
|
 – main.scss

from https://bit.ly/3P5Jn3g
