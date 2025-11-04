# 📺 TV Show Search App (using TVmaze API)

This is a simple web application that allows users to search for TV shows. It utilizes the free [TVmaze API](https://www.tvmaze.com/api) to fetch show data and display the results dynamically.

## 🚀 Live Demo

You can view the deployed project and test it live here:

**[View Demo](https://eric-front-end.github.io/tvmaze/)**

## 📖 Project Description

This project was built to practice asynchronous JavaScript, specifically making API calls (`fetch`) and handling the JSON response to dynamically update the DOM.

### Core Features

* **Search Functionality:** Users can enter a show title into the search bar.
* **API Integration:** The app sends a request to the TVmaze "Show Search" endpoint.
* **Dynamic Results:** The app parses the API response and creates a "card" for each matching show.
* **Data Display:** Each card shows the show's poster image and its title.
* **Responsive Layout:** The results grid is designed to be responsive and look good on various screen sizes.
* **Error Handling:** Displays a "No results found" message if the API returns an empty array for the query.

## 🛠️ Technologies Used

This project was built using core front-end technologies:

* **HTML5:** For the semantic structure, including the search form and the container for the results.
* **CSS3:** For all styling, including the search bar and the responsive grid layout for the show cards (using Flexbox or CSS Grid).
* **JavaScript (Vanilla JS):**
    * To capture user input from the search form.
    * To perform asynchronous API calls using the `fetch` API (with `async/await`).
    * To handle JSON data.
    * To dynamically create and append HTML elements to the DOM to display the search results.

## 🏁 Getting Started

If you want to run this project on your local machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Eric-Front-End/tvmaze.git](https://github.com/Eric-Front-End/tvmaze.git)
    ```

2.  **Navigate to the directory:**
    ```bash
    cd tvmaze
    ```

3.  **Open the project:**
    Simply open the `index.html` file in your preferred web browser. No special build steps are required.

## 🔌 API Credit

This project is powered by the free and easy-to-use **[TVmaze API](https://www.tvmaze.com/api)**.
