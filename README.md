# Digital Vortex

**Digital Vortex** is a game catalog project developed using React, Vite, and SCSS, integrating the RAWG Games API to display information about games, creators, stores, and more. The project is hosted on Vercel and can be accessed via the following link: [Digital Vortex](https://digital-vortex.vercel.app).

## Technologies Used

- React
- Vite
- SCSS
- Axios
- Redux Toolkit
- React Router

## Prerequisites

- Node.js installed (v14.x or higher)
- npm or yarn

## How to Run

1. Clone this repository:

    ```bash
    git clone https://github.com/seu-usuario/digital-vortex.git
    ```

2. Access the project directory:

    ```bash
    cd digital-vortex
    ```

3. Install the dependencies:

    - Using npm:

        ```bash
        npm install
        ```

    - Using yarn:

        ```bash
        yarn install
        ```

4. Run the project:

    - Using npm:

        ```bash
        npm run dev
        ```

5. The project will be available at [http://localhost:5173/](http://localhost:5173/) in your browser.

## Project Structure

Here's an overview of the project's structure:

- `src/api`: Contains the `axios.js` file for API call configuration and `api_key.js` with the RAWG API key.
- `src/assets/images`: Contains images such as banners, game details, sliders, loaders, and more.
- `src/components`: Folder with subfolders for different types of React components:
    - `common`: Components such as Banner, Navbar, Footer, and others.
    - `creator`: Components related to creators, such as CreatorItem and CreatorList.
    - `game`: Components related to games, such as GameDetails, GameItem, and GameList.
    - `genre`: Components related to genres, such as GenreItem and GenreList.
    - `store`: Components related to stores, such as StoreDetails, StoreList, and StoreItem.
- `src/constants`: Files with API URLs and constants.
- `src/layouts`: Contains `BaseLayout.jsx` for the main layout with Navbar and Footer.
- `src/redux`: Contains files related to Redux, such as slices and utils.
- `src/routers`: Contains `AppRouter.jsx` with the app's route configuration.
- `src/styles`: Contains SCSS files for global styling.
- `src/views`: Subfolders with pages for different sections of the app, such as creators, games, home, and stores.

## Features

- Viewing the list of games.
- Searching for games by name.
- Detailed viewing of games.
- Viewing creators and stores.
- Navigation between different routes in the app.
- Information about the Discord community on the HomePage.
- Newsletter in the footer to receive updates via email.

## Author

[Icaro] <icarofaria11@gmail.com>

## Useful Links

- [RAWG Games API](https://rawg.io/apidocs)
- [React Documentation](https://react.dev/)
- [Vite Documentation](https://vitejs.dev/guide/)
- [SCSS Documentation](https://sass-lang.com/documentation)

## Application Screenshots

