# Couchbase Lite iOS tutorial app

This repo contains the complete iOS app used in the tutorial for Couchbase Lite iOS. The tutorial shows how to bring the Couchbase Lite framework into your app, set up dependencies, create a database, and do basic CRUD operations. To focus on using Couchbase Lite, the app is highly simplified and provides only console output in the simulator. (There's no UI output other than a plain white background screen).

The code in the master branch is for an updated version of the tutorial, which is in progress. When that tutorial is published in late May 2014, I'll add a link to it here.

[Prerelease version 0.1.0](https://github.com/couchbaselabs/couchbase-lite-tutorial-ios/releases) is compatible with the [Couchbase Lite iOS 1.0 beta 2 tutorial](http://docs.couchbase.com/couchbase-lite/cbl-ios/index.html#tutorial).

## Downloading and running the tutorial app

1. Change to the directory in which you want to place the code:

	$ cd ~/repos

2. Clone the repository:

	$ git clone https://github.com/couchbaselabs/couchbase-lite-tutorial-ios.git

3. Change to the directory that contains the repo:

	$ cd couchbase-lite-tutorial-ios

4. In Xcode, open the project file found at **/couchbase-lite-tutorial-ios/HelloCBL/HelloCBL.xcodeproj**.

5. Add the Couchbase Lite framework to the app.

	* Download the [latest release of Couchbase Lite for iOS](http://www.couchbase.com/communities/couchbase-lite) and move it to a permanent location.

	* From the **Couchbase Lite** folder, drag the **CouchbaseLite.framework** folder to the **Frameworks** group in the Xcode project navigator.

	* In the **Choose options for adding these files** sheet, make sure that your app target is selected.

6. In the toolbar, choose an iOS simulator build scheme.

7. Click the **Build and then run the current scheme** button.

	You can view the app output in the console.

