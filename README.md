# Sample project to create Alexa Skill

- The skill is created on [Alexa Developer Console](https://developer.amazon.com/alexa/console/ask/build/custom/amzn1.ask.skill.e1c807c8-a6b5-455d-bff3-e1056eb78b00) and then imported on VS Code.
- Skill creation has 3 main sections - build, code and test
  - Build is for setting up the Intent (query to route to intents) and Slots (variables inside a query).
  - Code is for actual code flow for each Intent, which will be called as per the query setup on Build.
  - Test is the place where skill can be tested.
- Alexa hosted skill also has corresponding minimal resouces like S3, DynamoDB, Lambda, Cloudwatch etc.
- Cloudwatch can be used for debugging the routing of intents and other flow.
- VS Code also has a extension to test/simulate/debug alexa skill. (Install Ask CLI with this too)
- Once you create the skill, it will automatically be visible in your personal device's skill list, for proper publish, follow [this](https://developer.amazon.com/en-US/docs/alexa/alexa-for-business/create-and-publish-private-skills.html)
