## Pokedex

This project is a web-based Pokedex that showcases the first 151 Pokemon in a visually appealing and interactive way. It utilizes the PokeAPI to fetch data about each Pokemon, dynamically generating interactive cards for each entry.

**Features:**

* **Dynamically Generated Cards:** Each Pokemon is presented in a card format, displaying its name, serial number, type, and top three moves. 
* **Interactive "Load More" Functionality:** The Pokedex displays 10 cards initially. Users can click the "Load More" button to display additional 5 Pokemon cards, extending the list until all 151 Pokemon are shown.
* **Responsive Design:** The layout adapts seamlessly to different screen sizes, ensuring optimal viewing on desktops, tablets, and mobile devices.
* **AI-Generated Background:** The background image adds a unique and authentic feel, enhancing the overall aesthetic appeal.

**Technical Details:**

* **Languages:** HTML, CSS, and Javascript.
* **Framework:** Javascript Vanilla.
* **API Integration:** Uses PokeAPI to fetch Pokemon information.
* **Dynamic Content Generation:** Leverages Javascript functions like `map` and `slice` to dynamically generate the HTML for each Pokemon card, rendering the data from the API into interactive elements.
* **Responsive CSS:** Uses pure CSS techniques to ensure the Pokedex remains visually appealing on all screen sizes.

**How It Works:**

1. The `main.js` file fetches Pokemon data from PokeAPI using `fetch` and dynamically constructs the cards using DOM manipulation.
2. The `poke-api.js` file defines the API functions, fetching Pokemon details and converting the response into a user-friendly format.
3. The `pokemon-model.js` file defines the `Pokemon` class, providing a structure to hold the Pokemon data.
4. The `global.css` file sets up the global styling for the page.
5. The `pokedex.css` file styles the Pokedex elements, including the cards, their layout, and the responsive behavior.

**Installation:**

1. Clone this repository.
2. Open the `index.html` file in your web browser.
