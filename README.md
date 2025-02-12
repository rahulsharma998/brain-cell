# Users List App

This is a simple React app that fetches a list of users from the [JSONPlaceholder API](https://jsonplaceholder.typicode.com/users) and displays their information. It includes a search feature to filter users by their name.

## Features
- Fetches user data from the JSONPlaceholder API.
- Displays user name, email, and website.
- Search functionality to filter users by name.
- Displays loading and error states.
- If no users match the search query, a message will be shown indicating no results.

## Technologies Used
- **React**: JavaScript library for building user interfaces.
- **CSS**: Styling the app with a separate stylesheet (`App.css`).

## Deployed Link:-https://brain-cell-ruddy.vercel.app/

## Installation

To run the app locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/rahulsharma998/brain-cell.git
Navigate to the project directory:

```bash
cd users-list-app
```
Install dependencies:

```bash
npm install
```
Start the development server:

```bash
npm start
```
# How It Works
1. **Initial Load**:  
   When the app first loads, it makes an API call to fetch a list of users from [JSONPlaceholder](https://jsonplaceholder.typicode.com/users).
   
2. **Data Handling**:  
   The retrieved data is stored in the `users` state, and a loading message is shown until the data is successfully fetched.

3. **Search and Filter**:  
   A search bar allows users to filter the displayed list of users by their name. As users type, the displayed results update in real-time to match the search query.


---

# Error Handling
1. **API Request Failure**:  
   If the API request fails (due to network issues or server errors), an error message will be displayed with the error details.

2. **Loading State**:  
   While the data is being fetched, a loading message is displayed to inform users that the app is fetching the user data.

---

# Contribution Guidelines
We welcome contributions to improve this project! Here's how you can help:

1. **Fork**:  
   Feel free to fork this repository and make your changes.

2. **Submit a Pull Request**:  
   After making improvements, submit a pull request (PR) with a description of the changes you've made. We encourage you to provide as much detail as possible.

3. **Reporting Issues**:  
   If you find any bugs or encounter issues, please open an issue in the issue tracker with relevant details to help us investigate.

4. **Suggestions and Features**:  
   If you have any suggestions for new features or improvements, feel free to submit an issue or contribute directly by creating a pull request.

---

# License
This project is licensed under the **MIT License**. For more details, check the `LICENSE` file.
