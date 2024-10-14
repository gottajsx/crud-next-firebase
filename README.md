## Project Setup

Run the following command in your terminal
```bash
yarn create next-app next-firebase-crud
```

* Would you like to use TypeScript? No
* Would you like to use ESLint? Yes
* Would you like to use Tailwind CSS? Yes
* Would you like to use `src/` directory? Yes
* Would you like to use App Router? (recommended)? No
* Would you like to customize the default import alias (@/*)? Yes

## Dependencies Installation

```bash
cd next-firebase-crud
yard add firebase
```

## Firebase Setup

Create `.env file`, and copy-paste this code below that define variable value based on firebase config.
```
NEXT_PUBLIC_FIREBASE_API_KEY=api-key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=auth-domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=project-id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=storage-bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=sender-id
NEXT_PUBLIC_FIREBASE_APP_ID=app-id
```

## Tailwind Config

Clear some css variable at `src/styles/globals.css`:
```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```
## Run Project

Run the following command:
```bash
yarn dev
```