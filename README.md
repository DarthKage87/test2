# re-website
www.rationalexponent.com hugo website


This is the hugo website repository for www.rationalexponent.com

questions to @renstroost


In order to work with this:
- ensure you have hugo and all dependencies installed
- ensure you have aws cli installed, are authenticated, and have access to the www-test.rationalexponent.com bucket
- clone the repo
- develop locally, testing with:
  hugo server --buildDrafts --disableFastRender
- commit your changes to main!            
- when ready for approval testing, deploy with:
  hugo deploy --target test
  (test is the default target)

- when acceptance tests have passed, a second party should replicate the test deployment and then deploy with
  hugo deploy --target production

