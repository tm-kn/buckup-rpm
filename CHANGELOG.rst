0.1a3 - 19th March 2019
=======================

* Do not restrict boto3 version in the requirements.

0.1a2 - 27th June 2018
======================

* Fix no credentials error being not handled.
* Require Python version of at least 3.4.

0.1a1 - 27th June 2018
======================

* Update README.
* Update PyPI classifiers.
* Allow user to specify a list of paths that s3:getObject is set on rather than
  doing it on the whole bucket (#4).
* Set user access on bucket policy rather than IAM policy (#11).
* Don't require non-essential permissions and specify them in the README file
  (#12).

0.1a0 - 20th June 2018
======================

Initial release.
