## Welcome to Team 109!

Make sure to have the following dependencies/tools installed:
  - [VSCode](https://code.visualstudio.com/)
  - [Node.js (LTS)](https://nodejs.org/en)

Make sure to create an ssh key and add your public key to your GitHub account.
  - Create ssh key: [Link](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
  - Add public ssh key to GitHub: [Link](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)

#### To run locally:

After cloning the repo, run the following command in the root directory of the project:  
```bash
touch ./backend-api/.env && echo "PORT=4000" > ./backend-api/.env
```
(this just creates a file called `.env` in `./backend-api/` and writes `PORT=4000` to the newly created file)

---

To install the required dependencies:
  - `cd` into `./frontend` and run:
  ```bash
  npm install
  ```
  - Then `cd` into `./backend-api` and run:
  ```bash
  npm install
  ```

---

Then create two terminals both in the same project root directory.
  - In one, run:
  ```bash
  npm run app
  ```
  - In the other, run:
  ```bash
  npm run api
  ```

The application should be running at `http://localhost:3000`