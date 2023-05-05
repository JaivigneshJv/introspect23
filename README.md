# SEC Magazine (INTROSPECT 22')  [![Netlify Status]()]()

Web-page to view Saveetha Engineering College's annual Magazine - " INTROSPECT "

>Project is hosted on https://introspect23.netlify.app/  


## Table of Contents
- Getting Started
  - Prerequisites
  - Installation
  - Usage
- Features
- Built With
- Contributing
- License

## Getting Started
To get a local copy up and running follow these simple steps.

### Prerequisites
You should have Node.js and npm installed on your machine.

### Installation
1. Clone the repository:

```
git clone https://github.com/shanuflash/netflix
```

2. Install node packages:
```
yarn install
(or)
npm install
```

3. Create a supabase table named `netflix` with fields:
```
id: int8
userid: text
history: text[]
watch_list: text[]
```

4. Create a .env file in the root directory of the project with the following variables:
```
VITE_SUPABASE_URL=<YOUR_SUPABASE_URL>
VITE_SUPABASE_KEY=<YOUR_SUPABASE_KEY>
VITE_TMDB_API_KEY=<YOUR_TMDB_API_KEY>
```
You can obtain your Supabase URL and API key by signing up for a free account on supabase.io and creating a new project. You can obtain your TMDB API key by signing up for a free account on themoviedb.org and creating a new API key.

Usage
To run the project locally, run the following command in the terminal:

```
yarn dev
(or)
npm run dev
```
This will start a local development server at http://localhost:5173.

To build the project for production, run the following command:

```
yarn build
(or)
npm run build
```
This will create a production-ready build in the `dist/` directory.

## Built With
- ReactJS

## Contributing
Contributions are always welcome! If you have any ideas, bug reports, or pull requests, please feel free to open an issue or a pull request.
