# backbone
Learning.

Source - http://code.tutsplus.com/series/getting-to-know-backbonejs--net-24408

Part 1 :
- Backbone isn't considered true MVC – C is for Collection not Controller.
- Underscore is a utility library that provides enhanced functionality to JavaScript, adding additional functions for working with arrays, collections, functions and objects.

Models - 
- A model represents the data of an application. 
- To create a model in Backbone we just extend the Backbone.Model class using the extend() method.
- One of the properties we can set within this object is called defaults. This property allows us to configure default values for any attribute that we would like our models to have.
- Models have other properties that we can use to add functionality; we could define an initialize() method, and this method would be invoked automatically by Backbone for us when each model is initialized.

Collections -
- A collection is a class for managing groups of models.
- Like a model, a collection is a Backbone class that we extend to add custom functionality specific to our application.
- Collections also have an extend() method, and it accepts an object that allows us to set properties of the class and add behaviour.
- We use the model property to tell the collection what class each item in the collection should be built from..

Views -
- Views are responsible for displaying the data of the application in an HTML page. 
- One of the benefits of separating out the parts of the application that process the data and the parts that display the data is that we can very easily make a change to one, without requiring extensive changes to the other
- Just like models and collections, views have an extend() method used to extend the Backbone.View class

Micro Templating With Underscore
- Underscore provides the template() method as we saw to consume and interpolate templates
- In HTML page add the template that we can use to show data
