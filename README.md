VISIT: https://angular.io/docs/ts/latest/tutorial/ FOR MORE INFO

TUTORIAL: TOUR OF HEROES

The Tour of Heroes tutorial takes you through the steps of creating an Angular application in TypeScript.
The grand plan for this tutorial is to build an app that helps a staffing agency manage its stable of heroes.

The Tour of Heroes app covers the core fundamentals of Angular. You'll build a basic app that has many of the features you'd expect to find in a full-blown, data-driven app: acquiring and displaying a list of heroes, editing a selected hero's detail, and navigating among different views of heroic data.

You'll use built-in directives to show and hide elements and display lists of hero data. You'll create components to display hero details and show an array of heroes. You'll use one-way data binding for read-only data. You'll add editable fields to update a model with two-way data binding. You'll bind component methods to user events, like keystrokes and clicks. You'll enable users to select a hero from a master list and edit that hero in the details view. You'll format data with pipes. You'll create a shared service to assemble the heroes. And you'll use routing to navigate among different views and their components.
You'll learn enough core Angular to get started and gain confidence that Angular can do whatever you need it to do. You'll cover a lot of ground at an introductory level, and you'll find many links to pages with greater depth.

When you're done with this tutorial, the app will look like this live example / downloadable example.

The end game

Here's a visual idea of where this tutorial leads, beginning with the "Dashboard" view and the most heroic heroes:

Output of heroes dashboard
You can click the two links above the dashboard ("Dashboard" and "Heroes") to navigate between this Dashboard view and a Heroes view.

If you click the dashboard hero "Magneta," the router opens a "Hero Details" view where you can change the hero's name.

Details of hero in app
Clicking the "Back" button returns you to the Dashboard. Links at the top take you to either of the main views. If you click "Heroes," the app displays the "Heroes" master list view.

Output of heroes list app
When you click a different hero name, the read-only mini detail beneath the list reflects the new choice.

You can click the "View Details" button to drill into the editable details of the selected hero.

The following diagram captures all of the navigation options.

View navigations
Here's the app in action:

Tour of Heroes in Action
