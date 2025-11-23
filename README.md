# NewsApp

NewsApp is a React-based news application that fetches real-time news articles from the News API. It offers a clean and responsive interface for users to browse news across various categories.

## Features

- **Top Headlines**: Get the latest top headlines from the US.
- **Categories**: Browse news by categories such as Business, Entertainment, Health, Science, Sports, and Technology.
- **Infinite Scroll**: Seamlessly load more news articles as you scroll down.
- **Loading Bar**: Visual indicator for data fetching progress.
- **Responsive Design**: Optimized for various screen sizes.

## Tech Stack

- **Frontend**: React.js
- **Routing**: React Router DOM
- **API**: News API
- **Styling**: CSS, Bootstrap (if applicable, based on class names like `container`, `my-3`)
- **State Management**: React Hooks (`useState`, `useEffect`)

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

- Node.js and npm installed on your machine.
- A valid API key from [News API](https://newsapi.org/).

### Installation

1.  **Clone the repository:**

    ```bash
    git clone <repository-url>
    cd newsapp
    ```

2.  **Install dependencies:**

    ```bash
    npm install
    ```

3.  **Configure Environment Variables:**

    Create a `.env.local` file in the root directory and add your News API key:

    ```env
    REACT_APP_NEWS_API=your_api_key_here
    ```

### Running the Application

Start the development server:

```bash
npm start
```

The app will run at `http://localhost:3000`.

## Project Structure

```
src/
├── components/
│   ├── NavBar.js       # Navigation bar component
│   ├── News.js         # Main news feed component
│   ├── Newsitem.js     # Individual news article component
│   ├── Spinner.js      # Loading spinner component
│   └── ...
├── App.js              # Main application component
├── index.js            # Entry point
└── ...
```

## License

This project is open source and available under the [MIT License](LICENSE).
