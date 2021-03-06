This project is the implementation of a talk given at the Selenium Conference 2012 in London. 

The TastyMonster project is a test automation framework with a twist: in addition to outlining our own pet ideas as to how a Web Application should be modeled, this framework provides a rudimentary method, allowing you to generate the underlying pages and removing maintenance when the presentation layer changes out from under you.

PatentMojo is a simple (intentionally terrible) web application based on the Velocity and Wicket presentation layers. It has, in its automation/ folder, a set of classes that use the TastyMonster framework to generate a base set of Page objects, and you'll be able to see, as you change the Velocity templates (the *.vm files in WEB-INF/templates), re-running the TestPageGenerator class will re-generate these Base Page objects, giving you a real-time update to the state of the application.

Better documentation and unit tests will follow.

When configured properly, it will generate a set of Selenium Page Objects for use in automated test scripts. These pages will allow you to "absorb" changes made to the product under test, by analyzing the presentation layer and reflecting changes in this Page Object model.

It is split across two repositories under the mmerrell username: TastyMonster and PatentMojo. You'll need both to see an example of how to implement it, but if you're already familiar, you should just need TastyMonster.

We'll publish a Maven jar file as soon as the code base calms down and we believe we have a model worth sharing. Until then it's probably best to use the code itself and make customizations as needed.

For now, play around, enjoy, and remember--the concept is sound, as demonstrated on a major commercial web-app. This project is initially meant to provide more ideas than implementation, but we hope to make it grow over time into a real specification.

As word gets out about the power of this concept, we hope this project will serve as a beacon of unified terminology and process, allowing us to push for better change control within the industry.
