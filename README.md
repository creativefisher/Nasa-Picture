[![Deploy to DigitalOcean](https://mp-assets1.sfo2.digitaloceanspaces.com/deploy-to-do/do-btn-blue.svg)](https://cloud.digitalocean.com/apps/new?repo=https://github.com/creativefisher/Nasa-Picture/tree/master&refcode=b17a452d9947)

This sample demonstrates how to run a Dockerized Java application on DigitalOcean App Platform.  Since App Platform doesn't yet support Java, this sample shows how to accomplish this using Dockerfile.

This sample has been adapted from https://github.com/wkrzywiec/Nasa-Picture and simply calls an API to show the NASA picture of the day.

# Getting Started #

These steps will get this sample application running for you using DigitalOcean.

**Note: Following these steps will result in charges for the use of DigitalOcean services**

## Requirements

* You need a DigitalOcean account. If you don't already have one, you can sign up at https://cloud.digitalocean.com/registrations/new

## Forking the Sample App Source Code

To use all the features of App Platform, you need to be running against your own copy of this application. To make a copy, click the Fork button above and follow the on-screen instructions. In this case, you'll be forking this repo as a starting point for your own app (see [Github documentation](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo) to learn more about forking repos.

After forking the repo, you should now be viewing this README in your own github org (e.g. `https://github.com/<your-org>/aspnetcoresample`)

**Note:** You can skip forking this repo and select a sample app from the app creation page, however do notice that certain features will be disabled.

## Deploying the App ##

1. Visit https://cloud.digitalocean.com/apps (if you're not logged in, you may see an error message. Visit https://cloud.digitalocean.com/login directly and authenticate, then try again)
1. Click "Launch App" or "Create App"
1. Choose GitHub and authenticate with your GitHub credentials.
1. Under Repository, choose this repository (e.g. `<your-org>/aspnetcoresample`)
1. On the next two screens, leave all the defaults unchanged.
1. Click "Launch App"
1. You should see a "Building..." progress indicator. And you can click "Deployments"→"Details" to see more details of the build.
1. It can currently take 5-6 minutes to build this app, so please be patient. Live build logs are coming soon to provide much more feedback during deployments.
1. Once the build completes successfully, click the "Live App" link in the header and you should see your running application in a new tab

## Making Changes to Your App ##

As long as you left the default Autodeploy option enabled when you first launched this app, you can now make code changes and see them automatically reflected in your live application. During these automatic deployments, your application will never pause or stop serving request because the App Platform offers zero-downtime deployments.

## Learn More ##

You can learn more about the App Platform and how to manage and update your application at https://www.digitalocean.com/docs/apps/.


## Deleting the App #

When you no longer need this sample application running live, you can delete it by following these steps:
1. Visit the Apps control panel at https://cloud.digitalocean.com/apps
1. Navigate to the sample-dockerfile app
1. Choose "Settings"->"Destroy"

This will delete the app and destroy any underlying DigitalOcean resources

**Note: If you don't delete your app, charges for the use of DigitalOcean services will continue to accrue.**


## License
The MIT License (MIT)

Copyright (c) 2019 Wojciech Krzywiec

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
