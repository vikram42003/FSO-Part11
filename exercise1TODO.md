Language picked = Python

The points to discuss:

Q1) Some common steps in a CI setup include linting, testing, and building. What are the specific tools for taking care of these steps in the ecosystem of the language you picked? You can search for the answers by Google.

A. When setting up CI setup in java the first thing to do is set up a version control system like git, and then select a CI/CD tool like Github actions, Gitlab CI/CD, Jenkins etc and then you can create a config file for the CI tool to specify the automated actions that it should take like using maven to compile the code, junit to test, a java linting tool like checkstyle to lint.

Q2) What alternatives are there to set up the CI besides Jenkins and GitHub Actions? Again, you can ask Google!

A. Some alternatives to Jenkins and GitHub are CircleCI, GitLab, TravisCI or TeamCity by JetBrains which can easily be integrated with IntelliJ Idea ide for java which is also made by JetBrains

Q3) Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?

A. Since the team consists of only 6 people there is no need to self host the ci/cd platform since that would be quite complicated compared to cloud-based option. Although self hosted platform provides greater configuration, control and scalability the size of the team is small and there is no indication that the team size will increase and even if it does we will still be able to do all that we need to do with a cloud based option and we can take the decision to migrate to a self hosted option later down the line but for now cloud-based enviroment will suffice.
