# Choucroute

Choucroute is a Web Application with the goal of simplifying personal recipes management.

It is intended to be compatible with the [Cooklang](https://cooklang.org) Recipe Markup language and is build with the goal of writing recipes with this language inside a Web editor.

This project is in WIP, and is currently under active development.

### Roadmap

* [x] Manage recipes
* [x] Manage the inventory 
* [x] Manage the catalog 
* [x] Manage the shopping-list
* [ ] Manage users
* [ ] Create a Front-end application
* [ ] Add a Shops service
  * [ ] Schedules, notes and location thanks to [Google Maps API](https://developers.google.com/maps/apis-by-platform) / [OSM](https://www.openstreetmap.org/)
  * [ ] Information per ingredients (price, quality, carbon emission, ...) thanks to [OpenFoodFact API](https://world.openfoodfacts.org/data)

* [ ] Add a statistical service that shows information about your recipes/shopping. Idea of stats:
  - Number of recipes per month created
  - Most cooked recipe (used the most in the shopping card)
  - Most used ingredient
  - Most frequented store
  - Average time to shop, per month/week/
  - Preferred day and time to shop


### Technical Stack

This application is build on top of a micro-services architecture. It is composed of several services build with [Quarkus](https://quarkus.io) and a Frontend application in React.


### Contributing

This project is not production ready yet. When the first version of the application will be deployed, contributions were welcome.

### Contact

Created with 🍲 and 💭 in Mars 2023 by [GridexX](https://github.com/gridexx).

Arsène Fougerouse - [@GridexX](https://twitter.com/GridexX) - [arsene@r2devops.io](mailto://arsene@r2devops.io)