#Installation
## Make sure you have ['Node.js'](https://nodejs.org) installed on your machine.

1.Clone this GitHub repository to your computer using the following command:
```bash
git clone https://github.com/shadcn/ui-clerk-auth-next13.git
```
2.Navigate to the project directory:
```bash
cd ui-clerk-auth-next13
```
3.Install the dependencies using npm:
```bash
npm install
```
# Configuration
## Before running the server.
You need to set up the necessary environment variables for authentication.
Create a .env file at the root of the project and add the required values:
```bash
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=YOUR_CLERK_KEY
CLERK_SECRET_KEY=YOUR_CLERK_KEY
```
Make sure to replace YOUR_CLERK_KEY with your Clerk key. You can obtain this key by creating a [Clerk](https://clerk.dev].

# Running the Server
Once you have installed the dependencies and configured the environment variables, you can start the server using the command:
```bash
npm run dev
```
This will start the server and make your application accessible at the specified address (usually http://localhost:3000).
