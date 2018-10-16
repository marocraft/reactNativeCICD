# Description 

[![Build Status](https://app.bitrise.io/app/e6e12bb36eab0d28/status.svg?token=4El4-ooemJCALlSN5qzwPA&branch=master)](https://app.bitrise.io/app/e6e12bb36eab0d28)

Open source app for testing the Continuous Integration &amp; Deployment thanks to [Bitrise](https://www.bitrise.io/).

this Application use :
* [Jest](https://jestjs.io/)
* [Detox](https://github.com/wix/Detox)
# Set up on Bitrise
### Steps
* Login to [Bitrise](https://www.bitrise.io/) and **Click**  **+Add new app** .

* Connect your repository from your connected source code provider (Github, Bitbucket ...).

<img src="https://user-images.githubusercontent.com/30182093/46981453-4ab5bf00-d0d0-11e8-827b-a0f72de65e4d.png" alt="connect repository" width="100%" height="50%">

* Setup repository access for private repository, and no authentication required for the public ones.
  > See [DevCenter](https://devcenter.bitrise.io/getting-started/index/) for more details.
  
* Choose a branch for our scanner, this will help automation.

![choose branch](https://user-images.githubusercontent.com/30182093/46981713-75544780-d0d1-11e8-9e88-861e16bc30d3.png "center")

* Bitrise scanner will detect the project build configuration as we see.

![build configuration](https://user-images.githubusercontent.com/30182093/46981832-ea278180-d0d1-11e8-8684-bf631f1ad78e.png "center")

* Register a Webhook so that Bitrise can automatically start a build every time you push code into your repository.

![webhook](https://user-images.githubusercontent.com/30182093/46981987-75a11280-d0d2-11e8-9e98-6d9659018fe7.png "center")

* And thats all, Observe and Enjoy your first build! :boom:

![build](https://cdn.buttercms.com/gb2gLfrBSFSgzaOYFYCx)

* Now you are ready to learn some more about deployment
> Go here [DevCenter](https://devcenter.bitrise.io/)
