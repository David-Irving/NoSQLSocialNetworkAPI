# NoSQLSocialNetworkAPI
![University of Denver Logog](https://d92mrp7hetgfk.cloudfront.net/images/sites/misc/denver-switchup-thumbnail-a/original.png?1560210160)
## Acceptance Criteria
### GIVEN a command-line application that accepts user input
 |When       | Then
 | --------- |--------
 | I enter the command to invoke the application | my server is started and the Mongoose models are synced to the MongoDB database
 | I open API GET routes in Insomnia for users and thoughts | the data for each of these routes is displayed in a formatted JSON
 | I test API POST, PUT, and DELETE routes in Insomnia | I am able to successfully create, update, and delete users and thoughts in my database
 | I test API POST and DELETE routes in Insomnia | I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list

 ## Grading Requirements

**Note** If a Challenge assignment submission is marked as “0”, it is considered incomplete and will not count towards your graduation requirements. Examples of incomplete submissions include the following:
 * A repository that has no code
 * A repository that includes a unique name but nothing else
 * A repository that includes only a README file but nothing else
 * A repository that only includes starter code

### Deliverables: 10%
 * Your GitHub repository containing your application code.
### Walkthrough Video: 37%

 * A walkthrough video that demonstrates the functionality of the social media API must be submitted, and a link to the video should be included in your README file.
  * The walkthrough video must show all of the technical acceptance criteria being met.
  * The walkthrough video must demonstrate how to start the application’s server.
  * The walkthrough video must demonstrate GET routes for all users and all thoughts being tested in Insomnia.
  * The walkthrough video must demonstrate GET routes for a single user and a single thought being tested in Insomnia.
  * The walkthrough video must demonstrate POST, PUT, and DELETE routes for users and thoughts being tested in Insomnia.
  * Walkthrough video must demonstrate POST and DELETE routes for a user’s friend list being tested in Insomnia.
  * Walkthrough video must demonstrate POST and DELETE routes for reactions to thoughts being tested in Insomnia.
### Technical Acceptance Criteria: 40%
 * Satisfies all of the preceding acceptance criteria plus the following:
  * Uses the [Mongoose package](https://www.npmjs.com/package/mongoose) to connect to a MongoDB database.
  * Includes User and Thought models outlined in the Challenge instructions.
  * Includes schema settings for User and Thought models as outlined in the Challenge instructions.
  * Includes Reactions as the `reaction` field's subdocument schema in the Thought model.
  * Uses functionality to format queried timestamps properly.

### Repository Quality: 13%
 * Repository has a unique name.
 * Repository follows best practices for file structure and naming conventions.
 * Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.
 * Repository contains multiple descriptive commit messages.
 * Repository contains a high-quality README with description and a link to a walkthrough video.

### Bonus: +10 Points
 * Application deletes a user's associated thoughts when the user is deleted.

### Repository Link
 * https://github.com/David-Irving/NoSQLSocialNetworkAPI

### Preview of Application


https://user-images.githubusercontent.com/99232675/181654953-96ab65d1-a317-412b-8410-ff582677864d.mp4


