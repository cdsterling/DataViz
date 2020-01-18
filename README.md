# DataViz
Data Visualization Project for Kickstart Frontend Class


I have chosen to visualize data from the star wars api https://swapi.co/
For this initial data visualization i will be comparing the crew sizes of different starships.

in order to get this data the api is called like this:
	https://swapi.co/api/starships/<StarshipID#>/

where <StarShipID#> is the id number for a starship. So for example https://swapi.co/api/starships/9/ returns results (in json format) about the Death Star (technically it is a starship, although at somepoint there was confusion about it being a moon, i believe) which has a crew size of (according to the api) 342,953.

This comparison will be visualized using a bar graph.


My initial thought would be that it would be funny to see the crewsize comparison between the deathstar and the millenium falcon. but the difference is so drastic that it's kindof silly to see in a bar chart (342,953 vs 4).


for the starfield background i googled and found this awesome one put together by Keith Clark: https://codepen.io/keithclark/pen/zqcEd . It seemed very pertinent to the star wars theme.

note that i had to increase the z index of the bars in the bar chart in order for them to be clicked on.


Files:
 * README.md - This file containing relavant info about the project
 * index.html - the file showing the comparison bar graphs of a select number of ships from the Star Wars universe
 * css
   * reset.css - nothing to see here yet
   * style.css - all of the css used in index.css
