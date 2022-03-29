# Amazon Clone

Built using Next.js, Redux, TailwindCSS, Firebase

![Home Screen](/screenshots/home.png?raw=true)
![Orders Screen](/screenshots/orders.png?raw=true)
![Cart](/screenshots/cart.png?raw=true)

### Live Deployment

https://amazon-clone-dhruv-gursahani-1.vercel.app/

### Features

1. Full featured shopping cart
2. Services carousel
3. User's order page
4. Order Storage in Firestore
5. Stripe payment integration

### Note on Issues

For any bugs or errors in the project reach out to me on dhruv.gursahani@outlook.com

### Usage

#### Install Dependencies

- cd Amazon-Clone
- yarn install

### ENV Variables

1. GOOGLE_ID
2. GOOGLE_SECRET
3. FIREBASE_API_KEY
4. FIREBASE_AUTH_DOMAIN
5. FIREBASE_PROJECT_ID
6. FIREBASE_STORAGE_BUCKET
7. FIREBASE_MESSAGING_SENDER_ID
8. FIREBASE_APP_ID
9. FIREBASE_SERVICE_ACCOUNT_KEY
10. NEXTAUTH_URL
11. NEXTAUTH_SECRET
12. STRIPE_PUBLIC_KEY
13. STRIPE_SECRET_KEY
14. STRIPE_SIGNING_SECRET
15. HOST

- Variables 1-2 can be found in google cloud console

- Variables 3-8 can be found in firebase console (settings->project settings)

- Variables 10 and 15 are the domain of deployed project

- Variable 11 can be generated using the following command "openssl rand -base64 32"

- Variable 12 - 13 can be found in Stripe developer dashboard

- Variable 14 can be genrated by running "stripe listen --forward-to localhost:3000/api/webhook" in Stripe CLI

### Run

- yarn dev

### License

The MIT License

Copyright (c) 2022 Dhruv Gursahani https://dhruvgursahani.netlify.app

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
