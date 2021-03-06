# Angular.js

[Angular.js](http://angularjs.org/) is one of the hottest frameworks out there today and well worth learning.

## Data Binding Frameworks

 * Facilitate building [single page applications](http://en.wikipedia.org/wiki/Single-page_application)
   * Page never reloads
   * No server-side page rendering
 * Based on the [Model View Controller](http://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller) concept
 * Provide solutions for:
   * Routing - handling updates to the URL hash fragment
   * Templating - dynamically creating and updating HTML based on templates and models
   * Data binding - synchronize the model and user interface
 * Top data binding frameworks today:
   * [Angular.js](http://angularjs.org/)
   * [Knockout](http://knockoutjs.com/)
   * [Ember](http://emberjs.com/)
   * [JsViews](http://www.jsviews.com/#jsviews)
   * [Can.js](http://canjs.com/)
   * [Ractive](http://www.ractivejs.org/)

## Foundational Libraries

The following libraries lay the foundation for many data binding frameworks:

 * [jQuery](http://jquery.com/) - an industry standard library for [DOM](http://en.wikipedia.org/wiki/Document_Object_Model) [manipulation](https://api.jquery.com/category/manipulation/) and [AJAX](http://en.wikipedia.org/wiki/Ajax_(programming)).
 * [Underscore](http://underscorejs.org/) - a widely adopted [functional programming](http://en.wikipedia.org/wiki/Functional_programming) utility library, providing functional primitives such as map, reduce, each and filter. [Lo-Dash](http://lodash.com/) is a replacement for Underscore that boasts performance increases, bug fixes and additional features.
 * [Backbone](http://backbonejs.org/) - a tried and true bare bones MVC framework that provides fundamental features such as events, observable properties, and class-like inheritance. Backbone also has foundational support for routing based on hash fragments and RESTful synchronization with a [CRUD](http://en.wikipedia.org/wiki/Create,_read,_update_and_delete) backend for persistence.
 * [AMD](https://github.com/amdjs/amdjs-api/wiki/AMD) - an industry standard for separating JavaScript projects across many files using modules. The top AMD implementation is [Require](http://requirejs.org/).
 * [Promises](http://howtonode.org/promises) - an industry standard pattern for dealing with asynchronous control flow. The top Promises implementation is [Q](https://github.com/kriskowal/q). [Async.js](https://github.com/caolan/async) is another great asynchronous control flow library, from the [Node.js](http://nodejs.org/) community.
 * [Handlebars](http://handlebarsjs.com/) - one of the top templating libraries. Handlebars is derived from [Mustache](http://mustache.github.io/), which provides logic-less templates.

## Angular Learning Resources

Birds-eye-view:

 * [Learn Angularjs This Weekend](http://joelhooks.com/blog/2013/08/03/learn-angularjs-in-a-weekend/) - Advice on which resources to use for getting up to speed on Anguar.
 * [A Better Way to Learn AngularJS](http://www.thinkster.io/angularjs/GtaQ0oMGIl/a-better-way-to-learn-angularjs) - A great collection of links to resources for learning Angular.
 * [AngularJS-Learning](https://github.com/jmcunningham/AngularJS-Learning) - A kithen sink of links to Angular learning resources.

Introductory tutorials and guides:

 * [Angular Developer Guide Conceptual Overview](http://docs.angularjs.org/guide/concepts)
   * Enumerates fundamental concepts
   * Provides several code examples
 * [Official Angular Tutorial](http://docs.angularjs.org/tutorial)
   * Useful to read through
   * Emphasizes testing
   * Starts with complex boilerplate project
   * Great diagrams
 * [Egghead.io](https://egghead.io/tags/AngularJS)
   * A collection of short screencasts (scroll to the bottom for intoduction content)
 * [AngularJS Fundamentals In 60-ish Minutes](https://www.youtube.com/watch?v=i9MHigUZKEM)
   * A talk on YouTube that covers fundamentals of Angular
 * [Learn Angular.js in 30 Min](https://www.youtube.com/watch?v=QETUuZ27N0w)
   * A screencast showing how to build an app using [UI-Router](https://github.com/angular-ui/ui-router)
   * Does not cover basics, jumps to advanced usage
   * Great example of how development flows in practice

Design and implementation of Angular:

 * [Re-Imagining the Browser with AngularJS](https://www.youtube.com/watch?v=ersEb9vTX3Y)
   * Talk by Miško Hevery, creator of Angular
   * Discusses the high-level goals of Angular
 * [Bringing Angular Apps to Life with Animation by Miško Hevery](https://www.youtube.com/watch?v=cF_JsA9KsDM)
 * [Google I/O 2013 - Design Decisions in AngularJS](https://www.youtube.com/watch?v=HCR7i5F5L8c)

## Examples

These examples illustrate many Angular features with small increments.

Check them out in the [example viewer](./exampleViewer/).

 * [Example 1](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot01) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot01) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot01/index.html)) - Starter HTML page with a text input
 * [Example 2](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot02) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot02) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot02/index.html)) - Added keyup event listener on textInput.
 * [Example 3](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot03) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot03) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot03/index.html)) - Extracting text from the text input as it changes.
 * [Example 4](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot04) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot04) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot04/index.html)) - Updating a span when input text changes using the DOM API.
 * [Example 5](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot05) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot05) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot05/index.html)) - Updating a span when input text changes using jQuery.
 * [Example 6](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot06) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot06) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot06/index.html)) - Updating a span when input text changes using Backbone.
 * [Example 7](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot07) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot07) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot07/index.html)) - Updating a template when input text changes using Angular.
 * [Example 8](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot08) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot08) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot08/index.html)) - Data binding with many text inputs.
 * [Example 9](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot09) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot09) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot09/index.html)) - First name and last name.
 * [Example 10](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot10) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot10) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot10/index.html)) - Initializing the model using an Angular controller, defined with a global function.
 * [Example 11](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot11) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot11) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot11/index.html)) - Initializing the model using an Angular controller, defined within an Angular module.
 * [Example 12](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot12) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot12) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot12/index.html)) - Changing scope values asynchronously - updates don't propagate without .apply().
 * [Example 13](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot13) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot13) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot13/index.html)) - Changing scope values asynchronously - updates propagate .apply().
 * [Example 14](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot14) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot14) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot14/index.html)) - Looping over lists in templates using ng-repeat.
 * [Example 15](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot15) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot15) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot15/index.html)) - Adding entries to a list using forms and ng-submit.
 * [Example 16](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot16) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot16) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot16/index.html)) - Clearing the entered name on submit using data binding.
 * [Example 17](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot17) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot17) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot17/index.html)) - Removing names from a list using ng-click.
 * [Example 18](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot18) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot18) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot18/index.html)) - Enumerating objects - countries and their populations.
 * [Example 19](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot19) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot19) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot19/index.html)) - Building a table.
 * [Example 20](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot20) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot20) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot20/index.html)) - Fetching JSON.
 * [Example 21](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot21) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot21) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot21/index.html)) - Dependency injection syntax for minification.
 * [Example 22](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot22) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot22) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot22/index.html)) - Adding search using Angular filters.
 * [Example 23](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot23) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot23) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot23/index.html)) - Sorting in ng-repeat using orderBy
 * [Example 24](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot24) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot24) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot24/index.html)) - Sorting in descending order
 * [Example 25](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot25) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot25) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot25/index.html)) - Sorting table columns interactively.
 * [Example 26](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot26) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot26) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot26/index.html)) - Interactively reversing sort order.
 * [Example 27](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot27) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot27) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot27/index.html)) - Adding country flag images.
 * [Example 28](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot28) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot28) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot28/index.html)) - Using ng-src.
 * [Example 29](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot29) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot29) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot29/index.html)) - Adding capital data.
 * [Example 30](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot30) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot30) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot30/index.html)) - Adding GDP data
 * [Example 31](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot31) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot31) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot31/index.html)) - Formatting currency using Angular filters in templates.
 * [Example 32](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot32) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot32) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot32/index.html)) - Formatting population using Angular filters in templates.
 * [Example 33](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot33) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot33) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot33/index.html)) - Preparing for routing - making a simple country listing.
 * [Example 34](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot34) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot34) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot34/index.html)) - Getting started with routing using ngRoute
 * [Example 35](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot35) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot35) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot35/index.html)) - Moving templates for routes into separate files
 * [Example 36](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot36) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot36) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot36/index.html)) - Extracting and using parameters from routes
 * [Example 37](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot37) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot37) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot37/index.html)) - Using links with routes for navigation between views
 * [Example 38](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot38) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot38) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot38/index.html)) - Looking up details for a single country
 * [Example 39](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot39) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot39) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot39/index.html)) - Surfacing data on the country details page
 * [Example 40](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot40) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot40) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot40/index.html)) - Creating a service for loading the list of countries
 * [Example 41](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot41) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot41) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot41/index.html)) - Extracting the country details query into a service
 * [Example 42](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot42) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot42) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot42/index.html)) - Caching JSON data in a service.
 * [Example 43](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot43) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot43) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot43/index.html)) - Caching JSON using cache option
 * [Example 44](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot44) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot44) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot44/index.html)) - Creating a custom filter to encode URIs

by [Curran Kelleher](https://github.com/curran/portfolio) March 2014
