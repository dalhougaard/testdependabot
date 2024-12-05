# testdependabot

This repository was made to test creating automated pull requests from Dependabot alerts and assigning specific users to review the proposed changes. Security vulnerabilities can be introduced as code is expanded, so maintaining testing meant to combat introducing new vulnerabilities is important to the integrity of your project.

I chose this principle because I have gained interest in the security side of IT rather recently. As more and more people develop more and more tools to be use on and by computers, there is room for error and always room for bad actors. Maintaining a secure application should be the standard across the board. 

Dependabot will check your requirements or 'depends on' files and check if there are any known vulnerabilities in the specified versions of dependencies. Integrating these alerts into your CI/CD process will help keep things up to date as new vulnerabilities are discovered as well. Constant testing of dependencies that are not maintained by your organization is important to the security of your own application.

Pros of testing dependencies:
- Find vulnerabilities shared by the security community
- Implement automation to patch vulnerabilities before they can be exploited
- Be able to use third-party tools without compromising your own applications

Cons of testing dependencies:
- Contributes to testing and workflow times
- Can block important updates if testing system prevents when finding low level vulnerabilities
- Can disrupt development branches if not restricted to testing just before reaching main production branch