# Poké Card Atlas

Poké Card Atlas is a React single-page application for browsing Pokémon cards, creating personal card entries, managing a personal collection, and reviewing selected cards in a cart.

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

## Installation

Clone the repository:

```bash
git clone https://github.com/Nephyrustavelion/PokeCardAtlas_AIEng_M2.git