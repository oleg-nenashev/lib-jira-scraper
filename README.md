JIRA Scraper Library
================

JIRA API library for [Jenkins IRC Bot][1]. This library uses [JIRA REST API][2] provided by Atlassian and implements common actions with components and issues.

## Authentication

The library uses a <code>${user.home}.jenkins-ci.org</code> *.properties file to set credentials.
This file should contain <code>userName</code> and <code>password</code> variables.

License: [MIT License][3]

[1]: https://wiki.jenkins-ci.org/display/JENKINS/IRC+Bot
[2]: https://developer.atlassian.com/display/JIRADEV/JIRA+REST+APIs
[3]: http://jenkins-ci.org/mit-license
