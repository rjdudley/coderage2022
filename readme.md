# Delphi Enterprise CodeRage 2022 Slides #

The PDF contains all the slides and talking points from my talk "The Old and New of Enterprise Application Design".

If you'd like to see a replay of the talk, it's at [https://youtu.be/-NmDzVfofrk?t=8683](https://youtu.be/-NmDzVfofrk?t=8683).

If you have any questions/comments, you can find me online at [https://twitter.com/rj_dudley](https://twitter.com/rj_dudley).

I had an emphasis on security and zero trust, but without examples.  Just in the past few weeks, we've seen:

* [LastPass users: Your info and password vault data are now in hackers’ hands](https://arstechnica.com/information-technology/2022/12/lastpass-says-hackers-have-obtained-vault-data-and-a-wealth-of-customer-info/) (observability/monitoring on the compromised internal access, and the customer logging in may not be the user of the acocunt being logged into)
* [Infosys leaked FullAdminAccess AWS keys on PyPi for over a year](https://tomforb.es/infosys-leaked-fulladminaccess-aws-keys-on-pypi-for-over-a-year/) (observability/monitoring would be necessary to go back and look at unusual access)
* [Okta's source code stolen after GitHub repositories hacked](https://www.bleepingcomputer.com/news/security/oktas-source-code-stolen-after-github-repositories-hacked/) (not sure of the effect here yet, but Auth0 is a popular platform for OAuth/OIDC/SSO so those are now in doubt until keys are rotated)

Since you're interested in Delphi, you can find /n software's Delphi components at [https://www.nsoftware.com/platforms/delphi/](https://www.nsoftware.com/platforms/delphi/), and the C++ Builder editions at [https://www.nsoftware.com/platforms/builder/](https://www.nsoftware.com/platforms/builder/).  Plenty of components for SSL/TLS, encryption and authentication.  Be sure to follow /n software on Twitter at [https://twitter.com/nsoftware](https://twitter.com/nsoftware).