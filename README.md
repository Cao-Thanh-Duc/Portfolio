

## Setup 🔧

From your command line, first clone Cao Thanh Duc Portfolio:

```bash
# Clone the repository
$ git clone https://github.com/Cao-Thanh-Duc/Portfolio

# Move into the repository
$ cd dev-portfolio

# Remove the current origin repository
$ git remote remove origin
```

After that, you can install the dependencies either using NPM or Yarn.

Using NPM: Simply run the below commands.

```bash
# Install dependencies
$ npm install --legacy-peer-deps

# Force audit fix
$ npm audit fix --force

# Start the development server
$ npm start
```

Using Yarn: Be aware of that you'll need to delete the `package-lock.json` file if exists before executing the below commands.

```bash
# Install dependencies
$ yarn

# Start the development server
$ yarn start
```

Once your server has started, go to this url `http://localhost:3000/` to see the portfolio locally.
The page will reload if you make edits.

