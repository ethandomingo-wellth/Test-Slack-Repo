# Test Slack Repository

A test repository to see how slack webapp api works

Specifically this is a node script that messages a specific channel

## Steps for setting up Slack OAuth Token

1. Create Slack App with this [link](https://api.slack.com/apps) (navigate and click on green button that says Create Slack App)

2. Navigate to Slack settings and click on OAuth & Permissions

3. Scroll down to scopes and click on `Add an OAuth scope` under scopes

4. Add needed scopes (main ones I think we need are `chat:write` and `channels:join` but this is tentative for now and can change depending on later needs)

5. Then scroll up and under OAuth tokens click on install to workspace

6. It should give you a popup that allows you to login to your slack account. Once login, choose the slack workspace you want to add your app to (reccomended that you create a test workspace to play around with)

7. Finally, renavigate to settings->OAuth & Permissions for your slack app and you should have an OAuth token generated that you can copy and paste into your `.env` file
