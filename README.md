# Next.js 15 Boilerplate with TypeScript, Tailwind CSS, and MongoDB

This boilerplate is built using Next.js 15 with TypeScript for robust type safety, Tailwind CSS for modern and responsive styling, and MongoDB for database management. After setting up the project, create a `.env` file in the root directory and update it with your environment variables as shown below: 

MONGO_URI=<your_mongodb_connection_string>
NEXTAUTH_SECRET=<your_nextauth_secret_key>
NEXTAUTH_URL=<your_application_base_url>
ADMIN_ROLE=1
EMPLOYEE_ROLE=2
ACTIVE=1
INACTIVE=2

Once the `.env` file is configured, install dependencies using `npm install` and start the development server by running `npm run dev`. This boilerplate is designed to help you quickly build scalable full-stack applications with clear role definitions (`ADMIN_ROLE`, `EMPLOYEE_ROLE`) and status management (`ACTIVE`, `INACTIVE`). Happy coding!





