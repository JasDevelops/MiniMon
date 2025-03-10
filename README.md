# JAVASCRIPT APP (MiniMon) *Gotta Code 'Em All!*

*MiniMon* is a simple JavaScript project, that displays information about Pokémon. It uses **PokéAPI** to fetch its data and incorporates **Bootstrap** for styling and responsiveness.

---

## Table of Contents
- [Features](#features)
- [Technology Used](#technology)
- [Installation](#installation)
- [How to Use](#howTo)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## <a name="features"></a>Features:

- fully functional application
- dynamically loads a list of Pokémon from an external API (PokéAPI)
- it enables the viewing of data point in detail via bootstrap modal (showing name, height and image of Pokémon)
- designed to work on various screen sizes (responsive design) via bootstrap's grid system
- responsive navigation bar with toggle (hamburger) menu on small screens via bootstrap's navbar component
- swipe navigation within the modal to change from one Pokémon to the next
- displays custom loading message while fetching data
- search for specific Pokémon by name
- sort Pokémon by name or height

---

## <a name="technology"></a>Technology Used:

- **HTML5:** structure of application
- **CSS3:** Styling 
- **Javascript (ES6):** Functionality, incl. API requests, DOM manipulation, event handling and IIFE
- **Bootstrap 5.3:** responsive design and modals
- **PokéAPI:** data source for Pokémon information
- **GitHub Pages:** deployment platform

---

## <a name="installation"></a>Installation:

1. **Clone the Repository:**
   `git clone https://github.com/JasDevelops/MiniMon.git`

2. **Navigate to Project Folder**
   `cd MiniMon`

3. **Install Dependendencies**
   With npm: `npm install`  
   With yarn: `yarn install`
   
---

## <a name="howTo"></a>How to Use:

- Navigate the Pokémon list
- Click on a Pokémon to view its details in a modal
- Use the search bar to find specific Pokémon
- Sort the list by name or height using the dropdown

---

## <a name="contributing"></a> Contributing:

You are very welcome to contribute!

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature-branch`.
3. Commit your changes: `git commit -m 'Add new feature'`.
4. Push the branch: `git push origin feature-branch`.
5. Submit a pull request.

Please follow the code formatting guidelines and include tests for new features where applicable.

---

## <a name="license"></a> License:

This project is licensed under the MIT License. See the [License](./LICENSE) file for details.

---

## <a name="acknowledgements"></a>Acknowledgments:

- **PokéAPI** for providing Pokémon data
- **Bootstrap** for styling and responsive components
- **GitHub Pages** for hosting
- **CareerFoundry** for guidance
