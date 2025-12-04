# Build Fetch Display

This project is a simple web application that demonstrates how to fetch data from an API and display it on a webpage. It is built using HTML, CSS, and JavaScript, and is intended as a learning resource for beginners.

## Features
- Fetch data from a remote API
- Display fetched data dynamically on the page
- Responsive and clean user interface

## File Structure
```
index.html      # Main HTML file
styles.css      # CSS styles for the app
script.js       # JavaScript logic for fetching and displaying data
```

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, etc.)
- No installation required; all files are static

### How to Run
1. Download or clone the repository to your local machine.
2. Open `index.html` in your web browser.
3. The app will load and display data fetched from the configured API.

## How It Works
- The JavaScript in `script.js` uses the Fetch API to retrieve data from a remote endpoint.
- Once the data is received, it is parsed and rendered into the HTML structure.
- The CSS in `styles.css` ensures the app looks clean and is responsive.

## Customization
- To change the API endpoint, edit the URL in `script.js`.
- You can modify the HTML structure in `index.html` to change how data is displayed.
- Update `styles.css` to adjust the look and feel of the app.

## Example API

## APIs Used & Example Calls

Below are the exact APIs used in this project, with example calls:

### Dog API
- List breeds: `https://dog.ceo/api/breeds/list/all`
- Random image: `https://dog.ceo/api/breeds/image/random`
- Random image by breed: `https://dog.ceo/api/breed/{breed}/images/random`

### Cat API
- List breeds: `https://api.thecatapi.com/v1/breeds`
- Random image: `https://api.thecatapi.com/v1/images/search`
- Random image by breed: `https://api.thecatapi.com/v1/images/search?breed_ids={breedId}`

### Dad Joke API
- Random joke: `https://icanhazdadjoke.com/` (Accept: application/json)

### Weather API
- Geocoding: `https://geocoding-api.open-meteo.com/v1/search?name={city}`
- Weather: `https://api.open-meteo.com/v1/forecast?latitude={lat}&longitude={lon}&current_weather=true&temperature_unit=fahrenheit&windspeed_unit=mph`

### Currency Exchange API
- Latest rates: `https://open.er-api.com/v6/latest/USD`

### Cryptocurrency Prices (CoinGecko)
- Price: `https://api.coingecko.com/api/v3/simple/price?ids={coin}&vs_currencies=usd`

### Giphy GIFs
- Trending: `https://api.giphy.com/v1/gifs/trending?api_key={key}&limit=5&rating=pg`
- Search: `https://api.giphy.com/v1/gifs/search?api_key={key}&q={query}&limit=5&rating=pg`

### Movies (TMDB)
- Popular: `https://api.themoviedb.org/3/movie/popular?api_key={key}&language=en-US&page={page}`

### GitHub User
- User info: `https://api.github.com/users/{username}`

### Joke API
- Random joke: `https://v2.jokeapi.dev/joke/Any?type=single`
- By category: `https://v2.jokeapi.dev/joke/{category}?type=single`

### Public APIs List
- Markdown: `https://raw.githubusercontent.com/public-apis/public-apis/master/README.md`

### Advice
- Random advice: `https://api.adviceslip.com/advice`

### NASA APOD
- Astronomy picture: `https://api.nasa.gov/planetary/apod?api_key={key}`

### Trivia
- Random: `https://opentdb.com/api.php?amount=1`
- Custom: `https://opentdb.com/api.php?amount=1&type=multiple&category={cat}&difficulty={diff}`

### Number Fact
- Random: `https://corsproxy.io/?http://numbersapi.com/random/trivia`
- By number: `https://corsproxy.io/?http://numbersapi.com/{num}/trivia`

### Pokémon
- Random: `https://pokeapi.co/api/v2/pokemon/{id}`

### Star Wars Character
- Character: `https://swapi.py4e.com/api/people/{id}/`
- Species: `https://swapi.py4e.com/api/species/{id}/`

### Chuck Norris Joke
- Random: `https://api.chucknorris.io/jokes/random`

### Random User
- Random: `https://randomuser.me/api/`

### IP Geolocation
- Info: `https://ipapi.co/json/`

### Random Fox
- Random: `https://randomfox.ca/floof/`

### Random Duck
- Random: `https://corsproxy.io/?https://random-d.uk/api/random`

### Cat Fact
- Random: `https://catfact.ninja/fact`

### Dog Fact
- Random: `https://dogapi.dog/api/v2/facts`

### Random Food
- Random meal: `https://www.themealdb.com/api/json/v1/1/random.php`

### Science Trivia
- Random: `https://opentdb.com/api.php?amount=1&category=17`

### Random Cocktail
- Random: `https://www.thecocktaildb.com/api/json/v1/1/random.php`

### Kanye Quote
- Random: `https://api.kanye.rest/`

### Age Prediction
- Predict: `https://api.agify.io?name={name}`

### Gender Prediction
- Predict: `https://api.genderize.io?name={name}`

### Nationalize Prediction
- Predict: `https://api.nationalize.io?name={name}`

### Superhero
- All: `https://akabab.github.io/superhero-api/api/all.json`

### Random Meme
- Random: `https://meme-api.com/gimme`

### Random Fact
- Random: `https://uselessfacts.jsph.pl/random.json?language=en`

### Animal Fact
- Random: `https://catfact.ninja/fact`

### Random Country
- All: `https://restcountries.com/v3.1/all?fields=name,capital,flags`

### Historical Event
- Today: `https://history.muffinlabs.com/date`

### Random Book
- Fiction: `https://openlibrary.org/search.json?q=subject:fiction&limit=10`

### Sports Trivia
- Random: `https://opentdb.com/api.php?amount=1&category=21&type=multiple`

### Movie Trivia
- Random: `https://opentdb.com/api.php?amount=1&category=11&type=multiple`

### Math Fact
- Random: `https://corsproxy.io/?http://numbersapi.com/{num}/math`

### Cocktail Ingredient
- Random: `https://www.thecocktaildb.com/api/json/v1/1/random.php`

### Random Emoji
- All: `https://api.github.com/emojis`

### Planet Fact
- All: `https://api.le-systeme-solaire.net/rest/bodies/`

### Video Game Database (RAWG)
- Platforms: `https://api.rawg.io/api/platforms?key={key}`
- Games: `https://api.rawg.io/api/games?key={key}&page_size=5&platforms={platformId}&search={title}`

## Technologies Used
- **HTML5**: Structure and markup
- **CSS3**: Styling and responsive design
- **JavaScript (ES6+)**: Logic, API calls, and interactivity
- **Fetch API**: For making HTTP requests
- **Web Speech API**: For voice input functionality
- **LocalStorage**: For saving user preferences and data

## Browser Support
This app requires a modern browser with support for:
- Fetch API
- ES6+ features
- Web Speech API (for voice input)
- LocalStorage

Recommended browsers: Chrome, Firefox, Edge (latest versions).

## API Keys
Some features require API keys. The following are included in the code:
- **Giphy**: `rsDIb0Bf7arjRY0AXDwypNkjM8t1deOP` (replace with your own if needed)
- **TMDB**: `598792b69853292f72d8abc968c55698` (replace with your own if needed)
- **NASA**: `FrUiRHQ1NxpoweJFpWlZc1bp6zNtos59AlV30wYL` (replace with your own if needed)
- **RAWG**: `01ae668b962644f78afb895eebd326c9` (replace with your own if needed)

To get your own keys:
- Giphy: [developers.giphy.com](https://developers.giphy.com/)
- TMDB: [themoviedb.org](https://www.themoviedb.org/settings/api)
- NASA: [api.nasa.gov](https://api.nasa.gov/)
- RAWG: [rawg.io/apidocs](https://rawg.io/apidocs)

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## Acknowledgments
- Thanks to all the free APIs used in this project
- Icons and styling inspired by modern web design trends
This project is open source and available under the MIT License.

## Author
Created by Adam C.

---
Feel free to modify and expand this project for your own learning or development needs.