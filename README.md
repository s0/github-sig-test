# Git GPG Test Repo

Github recently announced [on their blog](https://github.com/blog/2144-gpg-signature-verification)
that they support displaying the status of GPG-Signed commits in commit lists.
This repo is to test these capabilities for a number of different signature
algorithms. You can see the result in the
[list of commits](https://github.com/samlanning/github-sig-test/commits/master).

Keys (avaliable as files in this repo):

* RSA 2048: `291EDC71` (Expires 2016-05-07)
* NIST P521: `E11EA17B` (Expires 2016-05-07)
* Curve 25519: `56342EDA` (Expires 2016-05-07)
