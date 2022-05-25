Hey! Nice to meet you ^^ ....
Gitlab CI will be run by file .gitlab-ci.yml
At branch master, as you can see there are 2 files:

Chatbot.gitlab-ci.yml
ViewerTool.gitlab-ci.yml

==> So we can't run CI by these files, what should we do?
Maybe you didn't notice we have 2 other branches right? Got ya:

Chatbot
ViewerTool

As purpose of each branch is displayed by its name.
Now if you want to run ViewerTool, just switch to branch ViewerTool. That's it.
A job can be trigger by:

Change in file: once you commit a change, CI will be run automatically
By button Run Pipeline
By schedule setup with Cronjob
