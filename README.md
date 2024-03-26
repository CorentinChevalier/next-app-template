This is a template for a Next.js project with TypeScript, ESLint, Prettier, Husky, Jest and Cypress pre-installed and pre-configured. All the settings are based on the official [Next.js](https://nextjs.org/) and [Prettier](https://prettier.io/) basic configurations, with some minor adjustments.

## Getting Started

# Run the development server with command line

First, to run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Run the development server with Docker

To run the development server with Docker, you can use the following command:

```bash
docker-compose up -d --build
```

This will launch a container with the development server running on port 3000. This container will be running in the background and it supports hot-reloading.

## Configuration

# ESLint

The base configuration is based on the official [Next.js ESLint configuration]()

# Prettier

The Prettier configuration is my personal configuration based on options that I found useful for a React project and the ones that I'm used to work with. You can change it in the `.prettierrc` file.

# Husky

The Husky configuration is set to run the `lint-staged` command before each commit. The `lint-staged` command will run Prettier on the files that are being commited.

## Testing

# Cypress

This project comes with Cypress pre-installed and pre-configured, for both E2E testing and Component testing.
To run the Cypress tests, you can use the following command:

```bash
npm run cypress:open
```

This will open the Cypress window where you can run the tests.

To run Cypress on the terminal, you can use the following command:

```bash
npm run cypress:run
```

# Jest

This project comes with Jest pre-installed and pre-configured. You can run the Jest tests with the following command:

```bash
npm run test
```

This will run all the tests in the `__tests__` folder.

## Learn More

To learn more about Next.js, take a look at the following resources:

-   [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
-   [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
