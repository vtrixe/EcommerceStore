Fashion-Ecommerce-Admin-Backend
A custom ecommerce admin backend for fashion businesses to build their online marketplaces.

Technologies Used
Technology	Benefit
TypeScript	Strong typing and modern features for JavaScript development.
Next.js 13 App Router	Server-side rendering and static site generation for fast and scalable web applications.
Shaden UI	A library of pre-built components for building user interfaces with Tailwind CSS.
Tailwind CSS	A utility-first CSS framework for building custom and responsive designs.
Prisma	A database toolkit for building next-generation data access layers.
Planetscale MySQL as ORM	A managed, scalable MySQL database service with a focus on reliability and performance.
Cloudinary	A cloud-based image and video management service for developers.
Stripe	A payment processing platform for online businesses.
Clerk	A user authentication and authorization platform for web applications.
Features
Add, edit, and delete products
Classify products to categories
Create custom billboards
Track orders
Single admin panel for multiple client-side applications
Getting Started Locally
To set up the project locally, you will need to have Node.js and NPM installed. Once you have Node.js and NPM installed, you can clone the repository and install the dependencies:

git clone https://github.com/your-username/Fashion-Ecommerce-Admin-Backend.git
cd Fashion-Ecommerce-Admin-Backend
npm install
Once the dependencies are installed, you can start the development server:

npm run dev
The development server will be running on port 3000. You can open the application in your web browser at http://localhost:3000: http://localhost:3000.

.env File Structure
The .env file is used to store environment variables for the application. The following is the structure of the .env file:

CLERK_PUBLISHABLE_KEY: The Clerk publishable key, which is used to initialize the Clerk SDK.
CLERK_SECRET_KEY: The Clerk secret key, which is used to sign and verify Clerk tokens.
CLERK_SIGN_IN_URL: The URL of the sign-in page.
CLERK_SIGN_UP_URL: The URL of the sign-up page.
CLERK_AFTER_SIGN_IN_URL: The URL to redirect to after a successful sign-in.
CLERK_AFTER_SIGN_UP_URL: The URL to redirect to after a successful sign-up.
DATABASE_URL: The URL of the database connection.
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME: The Cloudinary cloud name.
STRIPE_API_KEY: The Stripe API key.
FRONTEND_STORE_URL: The URL of the frontend store application.
STRIPE_WEBHOOK_SECRET: The Stripe webhook secret.


Dockerization
We are currently in the process of dockerizing this application so that setups are easier moving forward. We will provide instructions on how to run the application using Docker once the dockerization process is complete.

Conclusion
This custom ecommerce admin backend is a powerful tool for fashion businesses to build their online marketplaces. It is built with cutting-edge technologies and offers a wide range of features. We are excited to see how businesses use this backend to build successful online marketplaces.
