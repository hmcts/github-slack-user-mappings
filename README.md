# Github -> slack usernames

Used for notifying the user who made a change when their build has failed
 
Steps:
1. Retrieve the Slack Member ID from the Workspace Directory in Slack. Note that the Member ID is workspace specific!

Here's an article on how this can be done. 

https://medium.com/@moshfeu/how-to-find-my-member-id-in-slack-workspace-d4bba942e38c

2. Add the GITHUB ID and the Slack Member ID in the slack.json file in this repository in the format below:

{
    "github": "githubUserID",
    "slack": "slackMemberID"
}


