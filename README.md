# 🧑‍💻 Technical test

### Usage

Clone the repository: `$ git clone git@github.com:chiaratinmazian/technical-test.git && cd technical-test`

Install the dependencies: `npm install` or `yarn`

Start the server: `npm run dev` or `yarn dev`

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### Developing

You will fetch Github public repositories using the Github API and display their name in a list.
When the user clicks on a repository, they are redirected through this url: `localhost:3000/owner/repo` to a detailed page of the repository with the following information:

- its name
- the owner name
- the number of stars
- the number of watchers

On this page, when clicking on the repository's name, the user is redirected to its original Github page.

Github API documentation: https://docs.github.com/en/rest
