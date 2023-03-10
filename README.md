# Bay Area Coffee Shops, Cafes, and Bubble Tea Shops
## CS 448B Assignment 3
This visualization will show shops that lie in the intersection of the two circles and satisfies the price, rating, and search constraints. You can visit the Yelp site for each store by clicking any points on the map.  
  
In this assignment, we were tasked to make an interactive visualization software that shows all coffee shops, cafes, and bubble tea shops in a map of the Bay Area. Hovering over each shop’s point on the map shows a tooltip that visualizes important details, such as the store name, the rating, the price range, and the type of food they serve. Clicking over a point will take the user to the Yelp page so they can search for more details. The assignment also features four filters. The first one involves two draggable circles that will filter the restaurants based on whether they are located in the intersection of the two circles. The second and third filters allow users to distinguish between ratings and price range for each shop. The last filter is a basic implementation of a search bar that will filter the results if the input matches either a name, location, or a category of a store. All the results that are in the intersection of the two circles and satisfy the ratings, price range, and search constraints are visualized to the viewer, both in the map (with the circles having a different color) and as a list that is appended to the sidebar.  
  
Made in Javascript and d3.js.  
  
[View the project here](https://mhartenorio.github.io/sf-restaurants-js/).
