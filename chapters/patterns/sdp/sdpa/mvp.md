# Software Design Patterns / Architectural / Model View Presenter

* https://en.wikipedia.org/wiki/Model-view-presenter

Legend:

* The model is an interface defining the data to be displayed or otherwise acted upon in the user interface.
* The presenter acts upon the model and the view. It retrieves data from repositories (the model), and formats it for display in the view.
* The view is a passive interface that displays data (the model) and routes user commands (events) to the presenter to act upon that data.
