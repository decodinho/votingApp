# votingApp
voting application. This application is designed to store votes in a dynamoDB Database.
Once users have voted and hitten the vote button, an API is triggered. This API will also trigger a lambda function that will create and store the data in a dynamoDB bdd.
At the end of a voting process, a "result" button once hit will trigger an API, that will in turn trigger a Lambda function to calculate the maximum of votes related with each candidate.
A mail is sent by the system to the vote organizers.
