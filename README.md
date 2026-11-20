# News App – React Native

A mobile news application built using **React Native, Expo, and TypeScript**, powered by the NewsAPI. It allows users to browse the latest news, explore different categories, search for articles, and filter news based on their preferred country.

## Features

- **Latest News:** Fetch and display the latest news articles using NewsAPI.
- **Category Filtering:** Browse news across different categories.
- **Country Selection:** Choose a country to view region-specific headlines.
- **Search Functionality:** Search for news articles using keywords.
- **News Details:** View article images, titles, descriptions, authors, sources, and publication dates.
- **Infinite Scrolling:** Automatically load additional articles while scrolling.
- **Pull to Refresh:** Refresh the news feed to fetch the latest articles.
- **Loading & Error Handling:** Display loading indicators, error messages, and retry options.

## Tech Stack

- **React Native** – Cross-platform mobile application development.
- **Expo** – Development and application tooling.
- **TypeScript** – Type-safe application development.
- **NewsAPI** – Fetching news articles and headlines.
- **Expo Router** – Application navigation and routing.
- **Expo Image** – Efficient image rendering.
- **React Native Vector Icons** – Icons and UI elements.

## Project Structure

```text
News-App/
│
├── app/
│   ├── _layout.tsx
│   └── index.tsx
│
├── assets/
│   └── images/
│
├── components/
│   ├── header.tsx
│   ├── news-card.tsx
│   └── news-feed.tsx
│
├── config/
│   └── api.ts
│
├── services/
│   └── newsApi.ts
│
├── types/
│   └── news.ts
│
├── app.json
├── package.json
└── tsconfig.json
```

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/goutham-ketham/News-App.git
```

### 2. Navigate to the Project Directory

```bash
cd News-App
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure NewsAPI

- Obtain an API key from [NewsAPI](https://newsapi.org/).
- Edit the `.env` file in the project root directory.
- Add the following environment variable:

```env
EXPO_PUBLIC_NEWS_API_KEY=your_api_key_here
```

### 5. Start the Application

```bash
npx expo start
```

Run the application using an Android emulator, iOS simulator, or Expo Go.

## API Integration

This application uses the [NewsAPI](https://newsapi.org/) Top Headlines endpoint to retrieve news articles.

The API integration supports:
- Country-based news filtering.
- Category-based news filtering.
- Keyword-based news searching.
- Pagination for loading additional articles.

## Future Improvements

- Add bookmarks to save favorite articles.
- Implement dark mode.
- Add personalized news recommendations.
- Introduce detailed in-app article reading.

## License

This project is developed for learning and educational purposes.
