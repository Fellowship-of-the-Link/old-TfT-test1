# homepage spidergraph proposal
This is a short explanation of what I had in mind when I text-sketched out [the home page](README). Keep in mind this is a technology-agnostic wishlist item: if we can't do this it's not the end of the world.

The home page should be dominated by two elements:

* spidergraph: this displays each tool's scores across various dimensions, submitted via personal profiles and stored in an online data store
* "Find your ideal tools": this form allows the user to enter scores for each of the same dimensions, describing their ideal tool.

Ideally the spidergraph is immediately updated with the data the user entered via the form, displaying it as a tool labelled "My ideal tool". I imagine this could be achieved by using a tool like d3.js to create the spidergraph: it grabs the tool data from the online data store when the page loads, and is fed the user data when the user fills out the form.  




  
