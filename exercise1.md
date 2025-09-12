For this assignment we're going to be talking about Python programming language.

- Some common steps in a CI setup include linting, testing, and building. What are the specific tools for taking care of these steps in the ecosystem of the language you picked? You can search for the answers by Google.

For linting there are many possibilities like "pylint" and "Flake8". For testing "pytest" is used quite often, with which you can run both unit and integration tests. One other possibility is "unittest". For building and packaging Python projects, two popular options are "setuptools" and "wheel".

- What alternatives are there to set up the CI besides Jenkins and GitHub Actions? Again, you can ask Google!

For Python projects CI you can use also GitLab CI/CD operations, and you can run your GitHub repositories there also, although it's easier if you have your code also in GitLab. Other option could be "Travis CI" which can be used with YAML configurations and it also can be integrated with GitHub. Also "CircleCi" is a valid option for managing your CI projects in Python. 

- Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?

For a small team of six developers a cloud based solution would most likely be sufficient. It is easy to setup and use, it requires no hardware acquisitions, maintenance or back ups as the service provider will take care of all that. Cloud based services are also easyly scalable if the development needs get higher.

A self hosted system might be needed if there are special needs for example security reasons or workloads are very large, since cloud service pricing can be linked to amount of work and time. Also the cloud services might not be able to provide all of the specific tools or configurations the team needs.