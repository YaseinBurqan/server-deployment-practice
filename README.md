# server-deployment-practice

1. We create a new repository at GitHub, called
(server-deployment-practice).
   - Then select the “Add a README” option.
   - Then select the “Add a .gitignore” option, and choose Node.js.
   - Then choose the MIT license.
2. Deploy THE branch to `Heroku`.
3. Choose “GitHub”
4. Started to build our server like the demo to check if the routes is working.
5. we build the test file so we can `TDD` our code.
6. The link for Heroku applications, Github actions and the pull request.
7. Choose the “enable automatic deploys” option

   [Action Link](https://github.com/YaseinBurqan/server-deployment-practice/actions)

   [Heroku Dev Deploy](https://yasein-server-deploy-dev.herokuapp.com/)

   [Heroku Prod Deploy](https://yasein-server-deploy-prod.herokuapp.com/)

   [PR Link](https://github.com/YaseinBurqan/server-deployment-practice/pulls?q=is%3Apr+is%3Aclosed)

        Notes the Demo:

- Take step by step to create the Repo.
- Create new branch >> git checkout -b "dev"
- npm init -y
- npm i express dotenv jest
- npm i -d supertest
- Create server.js put the router on it.
- Create index.js require the server.
- Create middleware.
- Create Test
- to check the router is ok >> nodemon || node index.js.
- To test the server >> npm run test
- Update my readme file
- A C P
- Github action it should be passed.
- Create the HEROKU app and deploy it with GitHub.
