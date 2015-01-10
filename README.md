# slack-subversion
Subversion integration for Slack

1. Copy post-commit and slack-posthook.py to the hooks folder of your repo.
2. Enter actual TOKEN and DOMAIN for you Slack in slack-posthook.py
3. Change absolute path to slack-posthook.py on your server in post-commit

That's it. Python code hasn't any external or third-party library dependencies. And can be run with Python 2.6 And maybe lower or higher, just not tested.
