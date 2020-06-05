# dataviz - Module 8 | Creative Technology 
## Tiger King or Tiger Tyrant

This website contains a variety of data visualization regarding wild animals in captivity and in the wild, with a focus on big cats.

## Technical details
This project uses [JQuery](https://jquery.com) with [Kendo UI](https://www.telerik.com/kendo-ui) and [Bootstrap](https://getbootstrap.com) for a simple lightweight website without need for a back-end.

Partials are used to declutter the index page but keep the size of the website minimal.
JQuery is used to loop over all elements with a ```data-includeHTML``` parameter to include partials where needed.

To include a partial simply add a html element with the data-includeHTML parameter.  
```<div data-includeHTML="partials/_partial.html"></div>```

Data is either downloaded and stored in the project's data directory or collected remotely using API calls.

