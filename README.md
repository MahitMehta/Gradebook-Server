To Run Locally Run These Commands Before Starting the Server if on OSX

- export OBJC_DISABLE_INITIALIZE_FORK_SAFETY=YES
- rq worker
- rqscheduler

Set Worker Count:

heroku scale worker=10 -a gradebook-web-api