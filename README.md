# Poké Card Atlas

PokéCardAtlas is a Pokémon trading-card catalogue and collection web application built with React. It allows users to explore and filter Pokémon cards, add custom cards to their personal collection, manage collected cards, add cards to a cart, and complete a simulated checkout flow. The interface is designed around a clean, responsive card-based experience, with the screenshots below showing the main user journey from login to collection management and checkout.

<p align="center">
  <img src="ScreenshotsPrototype/PokeCardAtlas-01-Login.png" alt="PokéCardAtlas Login" width="49%">
  <img src="ScreenshotsPrototype/PokeCardAtlas-02-AddCardCatalog.png" alt="PokéCardAtlas Add Card and Catalogue" width="49%">
</p>

<p align="center">
  <img src="ScreenshotsPrototype/PokeCardAtlas-03-MyCatalog.png" alt="PokéCardAtlas Catalogue" width="49%">
  <img src="ScreenshotsPrototype/PokeCardAtlas-04-MyCollection.png" alt="PokéCardAtlas My Collection" width="49%">
</p>

<p align="center">
  <img src="ScreenshotsPrototype/PokeCardAtlas-05-MyCart.png" alt="PokéCardAtlas My Cart" width="49%">
  <img src="ScreenshotsPrototype/PokeCardAtlas-06-Checkout.png" alt="PokéCardAtlas Checkout" width="49%">
</p>

## Who It Is For

Pokémon card collectors who want a simple way to browse cards, keep a personal collection, add notes, and manage selected cards in one place.

## Live Demo

https://pokecardatlas.netlify.app/login

## Main Features

- Login and protected routes
- Browse Pokémon cards from the TCGdex API
- Search and filter cards
- Add custom card entries
- My Collection page
- Create, view, edit and delete custom cards
- Personal notes
- localStorage persistence
- Add cards to cart
- Remove and clear cart items
- Mock checkout confirmation

## Technologies Used

- React
- Vite
- React Router
- Context API
- useState
- useReducer
- TCGdex API
- localStorage
- Tailwind CSS / CSS
- Netlify

## Application Routes

- `/login`
- `/pokemon`
- `/collection`
- `/cart`

## Team Contribution

### Nelton

- TCGdex API integration
- Catalogue functionality
- Search and pagination
- API data handling
- GitHub deployment troubleshooting

### Donny

- Cart state management using useReducer
- Login / mock authentication flow
- BrowserRouter and protected routes
- Netlify deployment
- UI and styling improvements

### Andrew

- Implemented custom card CRUD
- Built My Collection page and route
- Added editable personal notes
- Added localStorage persistence
- Added image support for custom cards
- Integrated collection cards with cart
- Worked on routing and deployment troubleshooting
- Fixed TCGdex environment configuration issues
- Handled incomplete API card records


### Bonus Challenges Completed

- **Search and Filtering** – Added search and filtering functionality to help users find items in the catalogue.
- **Loading States** – Added loading indicators while asynchronous API data is being retrieved.
- **Responsive Design** – Optimised the interface for both desktop and mobile screen widths.
- **Mock Authentication Flow** – Implemented a login flow with protected routes to restrict access to authenticated users.
- **State Management** – Applied React state management and conditional rendering to support the additional functionality.
- **Improved User Experience** – Enhanced navigation and interaction across the application.

### AI and Tools Disclosure
- Figma AI — Used for UI/UX design, visual prototyping, and planning the application's interface.
- ChatGPT — Used for brainstorming, technical explanations, debugging, code review, and exploring implementation approaches.
- GitHub Copilot — Used for in-editor VScode suggestions, code completion, and development assistance.

## Installation

### Clone the repository:

```bash
git clone https://github.com/Nephyrustavelion/PokeCardAtlas_AIEng_M2.git

npm install
npm run build
npm run dev


