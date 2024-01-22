This is a LMS platform built in next.js with prisma as backend and many more api's.

Make sure to install node.js then run npm i.
After that add the following in .env file with all your api keys(app wont work without them)

also unzip app and add the app folder to the main directory of the app

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

DATABASE_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

MUX_TOKEN_ID=
MUX_TOKEN_SECRET=

STRIPE_API_KEY=s
STRIPE_WEBHOOK_SECRET=

NEXT_PUBLIC_TEACHER_ID=
