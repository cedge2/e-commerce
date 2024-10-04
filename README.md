"Practice E-commerce site using MERN stack"


This page allows users to sign up, sign in, browse items, purchase items, 
and use coupons.

It also includes an admin dashboard, where owner of store can upload new products,
and monitor sales stats over time.


Technologies used:
Git, Github, MongoDB, Express.js, React.js, Node.js, Tailwind, Vite,
Redis Upstash, Cloudinary, and more. Allows users to purchase items with Stripe.

To run on your own machine: 
Build command - npm run build
Start command - npm run start 

You can change the NODE_ENV variable to either production or development, 
and use the same commands - package.json is set to do this automatically


Deployment:
Deployed with [Render](https://render.com/) at [https://e-commerce-hk84.onrender.com/](https://e-commerce-hk84.onrender.com/)
This is hosted using free tier, so may take a while to load on first visit.

For environment variables, you will need:

PORT -> port you would like to run on

MONGO_URI -> your own [mongo](https://www.mongodb.com/) Url with your own username/password

UPSTASH_REDIS_URL -> Your own Url with [redis upstash](https://upstash.com/)

ACCESS_TOKEN_SECRET -> Your own random / secure secret password
REFRESH_TOKEN_SECRET -> A second random / secure secret password which is different from last

CLOUDINARY_CLOUD_NAME -> the name of your [cloudinary](https://cloudinary.com/) cloud
CLOUDINARY_API_KEY -> Your cloudinary api key
CLOUDINARY_API_SECRET -> Your cloudinary secret key

STRIPE_SECRET_KEY -> Your own key from [stripe](https://stripe.com/)

CLIENT_URL -> will be something like http://localhost:5173 if in dev, otherwise will be the url of deployed app
NODE_ENV -> should be either "development" or "production"
