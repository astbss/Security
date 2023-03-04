# Practical Application and Cloud Security

## Basic Checklists
- [Coding Rules and Guidelines](Coding_Rules_and_Guidelines.md)
- [Simple Linux Security](Simple_Linux_Security.md)

## Security Champions
This are some of my favorite Security Thought leaders
- [Tanya Janca](https://twitter.com/shehackspurple)
- [Marius Sandbu](https://msandbu.org/about-me/)
    - https://trusselsky.no/
    - https://github.com/msugn Microsoft Security User Group Norway
- [Marius Solbakken](https://goodworkaround.com/aboutme/)
- https://www.linkedin.com/in/chris-h-97680442/ Chris Hughes
- https://www.linkedin.com/in/clintgibler/ Clint Gibler
- https://www.linkedin.com/in/jameschip/ James Chiappetta
- https://www.linkedin.com/in/carolgv/  Carol Valencia 
- https://pragmaticwebsecurity.com/about.html  Dr. Philippe De Ryck
    - https://ndc-security.com/

## Security checklists
- https://github.com/krol3/container-security-checklist

## Session Management
It is my opinion as adviced from owasp.org and many others that only the session management features in your framework, or a third party tool/product used for this sole purpose, should be used to manage identity or a user session.

- https://wehackpurple.com/pushing-left-like-a-boss-part-5-4-session-management/
- https://cheatsheetseries.owasp.org/cheatsheets/Session_Management_Cheat_Sheet.html
- https://cheatsheetseries.owasp.org/cheatsheets/Session_Management_Cheat_Sheet.html#built-in-session-management-implementations
- https://stackoverflow.com/questions/20963273/spa-best-practices-for-authentication-and-session-management
- https://owasp.org/www-community/HttpOnly
- https://stackoverflow.com/questions/46356415/session-management-in-angularweb-api-application
- https://developer.okta.com/blog/2021/06/07/session-mgmt-node
- https://developer.okta.com/blog/2017/08/17/why-jwts-suck-as-session-tokens
- https://www.youtube.com/watch?v=zHBpJA5XfDk  Web App Pentesting - HTTP Cookies & Sessions


#### Example of Great Sessions Management
- https://flask-login.readthedocs.io/en/latest/
- https://auth0.com/blog/application-session-management-best-practices/
- https://www.youtube.com/playlist?list=PLBf0hzazHTGO3EpGAs718LvLsiMIv9dSC   Web App Penetration Testing

#### The Problem: Security Tokens in the Browser
- https://www.angulararchitects.io/aktuelles/part-1-the-problem-with-security-tokens-in-the-browser/
- https://datatracker.ietf.org/doc/html/draft-ietf-oauth-browser-based-apps-08
- https://www.angulararchitects.io/en/aktuelles/the-solution-easier-and-more-secure-with-authentication-gateways/
- https://medium.com/manomano-tech/why-we-should-no-longer-use-bearer-tokens-to-protect-sensitive-single-page-applications-a7597c6c3097
- https://www.youtube.com/watch?v=4V3GXPViXxQ  Hacking JWTs for Beginners with Farah Hawa

#### Microsoft Graph
- https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-on-behalf-of-flow
    - In the case of Single-page apps (SPAs), they should pass an access token to a middle-tier confidential client to perform OBO flows instead.

## Security Tools
- [CloudKnox Permissions Management](https://www.microsoft.com/en-us/security/business/identity-access-management/permissions-management) 
- https://www.youtube.com/playlist?list=PLBf0hzazHTGO3EpGAs718LvLsiMIv9dSC
- https://code.google.com/archive/p/skipfish/wikis/SkipfishDoc.wiki

## More APP security Articles
- https://security.googleblog.com/2011/05/website-security-for-webmasters.html
- https://angular.io/guide/security

## CIS Cybersecurity Benchmarks
- https://www.cisecurity.org/benchmark
- https://github.com/ansible-lockdown/UBUNTU20-CIS
- https://github.com/ansible-lockdown/AZURE-CIS
- https://github.com/ansible-lockdown/Windows-2019-CIS
- https://github.com/alivx/CIS-Ubuntu-20.04-Ansible


## Better App Sec
- https://wehackpurple.com/about/
- https://betterappsec.com/cisos-guide-to-a-modern-appsec-program-a6021f52e62d
- https://betterappsec.com/how-to-scale-appsec-with-security-champions-d92f4d09021c
- Built a central application inventory
- Inventory the apps into components where possible
- https://betterappsec.com/how-to-prevent-security-breaches-with-appsec-pentesting-ba4100645994
- https://attack.mitre.org/ Globally-accessible knowledge base of adversary tactics and techniques based on real-world observations.
- https://techbeacon.com/security/7-must-dos-delivering-app-focused-security

# Microsegmentation
- https://www.paloaltonetworks.com/cyberpedia/what-is-microsegmentation
- https://www.gartner.com/smarterwithgartner/gartner-top-10-security-projects-for-2018
- https://cdn2.hubspot.net/hubfs/407749/Downloads/Illumio_eBook_The_Definitive_Guide_to_Micro_Segmentation_2017_08.pdf
