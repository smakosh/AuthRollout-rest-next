# Roll Your Own Auth

Roll Your Own Auth is a TypeScript project that provides a flexible authentication system for your web applications.

This boilerplate is one of incoming boilerplates, this one leverages Next.js making requests to a REST API that implements authentication using session-based storage in Redis, the user id is then securely stored in HTTP-only cookies.

This specific project requires the following [REST API](https://github.com/smakosh/AuthRollout-rest-express)

## Getting Started

1. Setup environment variables
2. Install dependencies

```bash
pnpm i
```

3. Start your server

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

This project uses [`shadcn/ui`](https://ui.shadcn.com/) which provides UI components ready to copy paste manually or via their CLI, it uses [`radix-ui`](https://www.radix-ui.com/).

## Todo

- [x] Cleanup code
- [x] Add middleware
- [ ] Handle server side errors
