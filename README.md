# User Card Grid 📊

A simple web page displaying user cards in a grid format. Users are fetched from the [Reqres](https://reqres.in/) API, and their information is dynamically rendered on the page.

## Features 🚀

- Responsive user card grid.
- Fetches user data from the Reqres API.
- Loading state with a loader animation.
- Error handling for failed API requests.

## Quick Start 🏁

1. Clone this repository.
   ```bash
   git clone https://github.com/yourusername/your-user-card-grid-repo.git
   ```

2. Open the `index.html` file in a web browser.

3. Click the "Get Users" button to fetch and display user cards.

## Technologies Used 🛠️

- **HTML**
- **CSS**
- **JavaScript**

## API Used 🌐

- [Reqres API](https://reqres.in/)

## Structure 🏗️

- **Navbar:** Displays the brand name and a button to fetch users.
- **User Grid:** Dynamically populates user cards in a grid layout.
- **User Card:** Represents an individual user with their avatar, name, and email.

## Code Explanation 📝

- The `getUsers` function is triggered when the "Get Users" button is clicked.
- The function makes a fetch request to the Reqres API to get user data.
- User cards are dynamically created and inserted into the user grid.
- Loading and error states are handled for a better user experience.

**Happy coding!** 🚀
