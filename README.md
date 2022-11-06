# React.JS movies platform

responsive website movies platform

with home page to get popular and top rated movies ,filter movies ,movie details page , pagination

using React.JS ,swiper
@reduxjs/toolkit
react-redux
react-router-dom
redux-thunk
tailwindcss
daisyui
postcss
vite

## API Reference

#### Get all popular movies

```http
  GET /movie/popular
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get the primary information about a movie.

```http
  GET /movie/{movie_id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### Get the top rated movies on TMDB.

```http
  GET /movie/top_rated
```

| Parameter | Type      | Description                                |
| :-------- | :-------- | :----------------------------------------- |
| `id`      | `string`  | **Required**. Id of item to fetch          |
| `page`    | `integer` | **optional**. Specify which page to query. |

## Installation

Install my-project with npm

```bash
  cd React.JS movies platform
  npm install
  npm run dev
  npm run build
  cd build
  cp index.html 200.html
  surge
```

## Acknowledgements

- [swiperjs](https://swiperjs.com/demos#space-between)
- [redux-toolkit](https://redux-toolkit.js.org/)
- [react-router](https://reactrouter.com/en/main)
- [redux-thunk](https://redux.js.org/usage/writing-logic-thunks)
- [tailwind css](https://tailwindcss.com/)
- [daisy ui](https://daisyui.com/)
- [vite js](https://vitejs.dev/)
- [hero icons](https://heroicons.com/)
- [surge](https://surge.sh/)

## Demo

link to demo

[deployed on surge ](https://industrious-digestion.surge.sh/)

[deployed on netlify](https://fluffy-cuchufli-91a178.netlify.app/)

![img1](img3.png?raw=true "Title")
![img1](img1.png?raw=true "Title")
![img1](img2.png?raw=true "Title")
![img1](img4.png?raw=true "Title")
![img1](img5.png?raw=true "Title")

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
