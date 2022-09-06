# The fanpage exercise

<img src="https://github.com/Aarkan1/exercises/raw/main/the-fanpage/assets/fanpage-banner.png" alt="fanpage-banner" style="width: 100%; max-width: 700px;">

Build a fanpage for your favorite genre. It starts small, but has huge possibilities to be a long term project. 

Work solo or in groups. 

The functionalities below isn't prioritized. You can do them in any order you like.

Recommend doing the basics first with minimal styling. If you get the time you could look at the **Design inspirations** and try to implement better styling.

### Getting started

Start off by creating a new directory for the exercise. 
Follow up by installing React with React Router Dom in that directory. 

- React TypeScript installation
    - `npx create-react-app frontend --template typescript`
    - `npm install react-router-dom@6 @types/react-router-dom`
- React JavaScript installation
    - `npx create-react-app frontend`
    - `npm install react-router-dom@6`

### Basic functionality

- A landing page including:
- Images with titles in a list of cards. Clicking the card or a button should route to a details page.
- A details page with more information. Should fetch data relevant to an id in the url.
- Data should be fetched via an API or importing a JSON-file. _(recommend the API approach)_

### Advanced functionality

- Add a search input to the landing page to filter data.
- Enable sorting of data on specific properties.
- Add bookmarks/favorites where you can save a character/movie.
- Be able to remove a bookmark/favorite.
- Responsive design that works on both mobile and desktop.
- Persist bookmarks/favorites between page reloads. _(localStorage, indexedDB, etc)_

### Epic functionality

- Add user registration and authentication to personalize bookmarks/favorites. _(only frontend)_
- Add a complete REST backend with a database to handle security and fetching data.

### API links
<img src="https://github.com/Aarkan1/exercises/raw/main/the-fanpage/assets/movies-banner.png" alt="movies-banner" width="400">

- Movies API: https://www.omdbapi.com/

<img src="https://github.com/Aarkan1/exercises/raw/main/the-fanpage/assets/heroes-banner.jpg" alt="heroes-banner" width="400">

- Superheroes API: https://www.superheroapi.com/
- [Superheroes JSON](https://raw.githubusercontent.com/Aarkan1/exercises/main/the-fanpage/assets/superheroes.json)

<img src="https://github.com/Aarkan1/exercises/raw/main/the-fanpage/assets/pokemon-banner.png" alt="pokemon-banner" width="400">

- Pokémon API: https://pokeapi.co/
- [Pokémon JSON](https://github.com/Aarkan1/exercises/raw/main/the-fanpage/assets/pokemon.json)

### Design inspiration

![movies-design](https://github.com/Aarkan1/exercises/raw/main/the-fanpage/assets/movies-design.jpg)

<br>

![pokedex-design](https://github.com/Aarkan1/exercises/raw/main/the-fanpage/assets/pokedex-design.png)