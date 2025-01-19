# Blogging App Client

This is the frontend of the Blogging App, a platform where users can read, write, and share articles. The frontend is built using React and integrates with a backend server to manage data.

## Features

- User authentication (login, registration)
- Create, edit, delete, and view articles
- Comment on articles
- User profile management
- Admin dashboard for managing posts, comments, and users

## Project Structure
blogging-app-client/ ├── .gitignore ├── LICENSE ├── README.md ├── package.json ├── public/ │ ├── images/ │ ├── index.html │ ├── manifest.json │ └── robots.txt ├── src/ │ ├── App.css │ ├── App.js │ ├── assets/ │ ├── components/ │ ├── constants/ │ ├── data/ │ ├── hooks/ │ ├── index.css │ ├── index.js │ ├── pages/ │ ├── services/ │ ├── store/ │ └── utils/ └── tailwind.config.js


## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher) or yarn (v1.22 or higher)

### Installation

1. Clone the repository:

```sh
git clone https://github.com/your-username/blogging-app-client.git
cd blogging-app-client

2. Install dependencies:
npm install
# or
yarn install

Running the Project
Start the development server:
npm start
# or
yarn start

This will start the development server and open the application in your default web browser.

Building for Production
To create a production build of the application, run:

npm run build
# or
yarn build

This will create an optimized build of the application in the build directory.

Environment Variables
The project uses a proxy to connect to the backend server. Ensure that the backend server is running on http://localhost:5000 or update the proxy field in package.json if the backend server is running on a different URL.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes.

Contact
For any inquiries, please contact suryascodeverse@example.com or chauhanaman1912@gmail.com