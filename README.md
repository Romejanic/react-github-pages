# react-github-pages
A template for deploying a React app to Github Pages.

## How does it work?
1. Checkout and edit the React code like any other React app.
2. When you want to make a release deployment, go to Github.
3. Run the "Deploy App" Github Action.
4. (First time setup only) When it is done, set up a Github Pages deployment on the `deploy` branch.

When running the deploy action, Github will create an empty branch, compile the React code and then commit
any changes. Github Pages will automatically redeploy so no more manual setup is needed to run releases.