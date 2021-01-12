# A Test Mail Server for a PHP Docker Container
For a small PHP project, I created a Docker container with an Apache and PHP in order to ease local development and setup. But that was not enough because my PHP application also sends mails and I wanted to test this feature locally as well. That’s why I needed a local SMTP server for testing and integrate it into my current Docker composition. In this brief post, I show you how I achieved this.

