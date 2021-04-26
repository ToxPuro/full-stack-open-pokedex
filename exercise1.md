My hypothetical programmer team used python for their application.

Linting is done by python specific linter called pylint. Pylint just like eslint notices style errors that have been configured in rc-file, but it also gives the code a rating based on how well it matches the style guide. This gives the option of some flexibility to the linter by setting a goal rating, which must be achieved and the whole pipeline doesn't fail just because of one style error. 

For testing this python application the team uses pytest. With pytest it is possible to write unit and integration tests. Pytest can give coverage report so we know which code is covered by tests and which are not. Also with the coverage report it is possible to track the coverage percent and show it in their repository in github (this team uses github). 

Since the team uses python which is interpreted language there is no need for a build step at all.

With googling I found a long list of alternatives including: CircleCI, TeamCity, Bamboo, GitLab, Buddy, Travis CI, Codeship, GoCD, Wercker, Semaphore, Nevercode, Spinnaker and Buildbot (for Python). 

Since this developer team is relatively small it is probably smart to use cloud-based options as is suggested in the learning material.
The team made their cost calculations and chose cloud-based option since it was cheaper and their application doesn't have any special requirements.
