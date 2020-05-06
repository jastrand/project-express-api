# Express API Project

My first API built using Express! You can use the endpoints below to access different data (from netflix):

/titles - Data for all netflix titles included in the API. The result will come back with 20 results on every page, to access different page: 

/titles?page={pageNumber} - Starting from page 1


/titles/${id} - Data for a specific title ID from the json file. 

/year/2019 - Data for a specific release year. 

/type/movie - Data for only movies

/type/tvshow - Data for only TV Shows

## Tech learned

- How to build API in Node using Express
- How to create routes in Express
- Postman
- Practice data manipulation in JavaScript - selecting, filtering, and limiting arrays

## View it live

https://golden-globe-technigo.herokuapp.com/

(confusing name? It was a golden globe API at first)
