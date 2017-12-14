**IBM 12/10/2017**

# ***iOS App Distribution***

I. Summary

II. Need

III. Options - Overview

IV. Options - Pros and Cons

V. TESTFLIGHT

VI. HOCKEY APP

VII. MAAS360 - Introduction

VIII. Appendix

# I.Summary

This document gives reader a brief overview of options that are
available to distribute iOS App for usage and testing.

The goal is also to identify and describe each option of distribution
and their use cases. This document will also introduce some trending
distribution option widely used in industry for testing and Adhoc
purposes.

# II.Need

In today’s world of rapid App development, every client has a unique
need of deployment and distribution. To better understand the client’s
need and provide correct solution we need to first understand the
options that are available to us in the Apple ecosystem.

**Some of the core areas that we are trying to focus here are:**

  * Scenarios of distributing the App.

  * Distribution options, their features and limitations

  * Distribution channels for Adhoc and Testing

  * Third party MDM solutions, MAAS 360.

# III.Options - Overview

<img src="./media/image1.png" width="642" height="180" />

## 1.iTunes App Store.

> The most preferable method to distribute an iOS App is through Apple’s
> App store. The iTunes App Store allows you to price your application
> anywhere between free and $999. Developer who wishes to sell his app
> on App store has to pay apple 30% of the cost.
>
> The developer can determine the countries/regions where the app is
> sold but cannot restrict who can purchase/download the app within
> those regions.
>
> There is an optional educational discount you can provide for
> qualifying institutions.
>
> App updates are free to users and are distributed easily through the
> App Store.
>
> All apps are reviewed by Apple prior to inclusion. Developers can
> either use enterprise or individual subscription to distribute their
> App via Appstore

## 2.Apple Apps Store B2B Program

> In many ways similar to the traditional App Store, the B2B program
> allows you to restrict your app to specific businesses who are also
> registered in the program. If you want the benefits of the App Store
> distribution method but it is not appropriate to have your app
> generally available in the store (i.e. it is customized for a certain
> business), this program can be a good alternative.
>
> The B2B program has the same 70/30% split and payment characteristics
> as the mainstream App Store.
>
> This program supports optional volume discounts for customers
> purchasing larger quantities.
>
> App updates are free to users and are distributed through the App
> Store. This method allows the use of In-App Purchase and iCloud APIs.

All apps are reviewed by Apple prior to inclusion.

## 3.Apple Enterprise Developer Program

> If you are creating an app for use inside your business, the
> Enterprise Developer Program allows you to distribute that app to your
> employees, inside your company.
>
> This program does not have a limit on the number of devices per app
> and does not require per-device registration for constant builds like
> ad-hoc beta testing does, though it does require that each device be
> submitted as a member of the organization’s program.
>
> You are not allowed to sell access to apps in the Enterprise Developer
> Program – doing so is against the guidelines and will get you booted
> from the program. Also, apps deployed this way are not eligible for
> In-App Purchase.
>
> This program is used by many Fortune 500 companies to create apps
> internal to their employees.
>
> The Enterprise Developer Program costs $299/year and a valid DUNS
> number. A previous restriction that required applicants to have at
> least 500 employees has been dropped.

## 4.Subscriptions 

> Many enterprise apps interact with a remote service to provide their
> data. Those services are often billed to customers through an annual
> subscription or support contract.
>
> Like app purchases, Apple requires in-app subscriptions to follow the
> same 70/30% revenue split, if the service subscription is referenced
> in the app (i.e. ‘go to our Web site to sign up for service xyz’).
>
> Alternatively, if you do not reference the subscription in the app,
> you are not required to share any revenue with Apple.
>
> If you are developing In-App Purchase subscriptions or additional
> content, it’s a very good idea to review the updated App Store
> guidelines to ensure you are compliant.

# IV.Options - Pros and Cons

## 1.The Public App Store

> Distribute the app on the public App Store. Only people authorized to
> use the app can authenticate and use its features. Requiring a small
> price (such as 99 cents) will discourage casual installations.
>
> Submitting to the public App Store requires an iOS Developer license
> for $99 per year.

**Pro’s**

  * Apple provides the distribution service – The App Store. It is
    highly available and well understood by users.

  * The App Store promotes your company on a highly visible marketplace.

**Con’s**

  * The App Store approval process is required for initial app
    deployment and app updates. You may be required to make changes to
    the app. The approval process can take a few days or a few weeks.

  * The App Store provides information about your app to competitors
    including a description of the app’s features, screenshots and an
    indication when the app is updated.

  * If you charge a price for the app, 30% of the revenue goes to Apple.

 

## 2.iOS Developer Enterprise Program

> The iOS Enterprise Distribution program allows a company to distribute
> their own “in-house” apps directly. It is intended for employees of
> the licensee company only and that licensee must be a company or
> organization with a DUNS number.
>
> The cost is $299 per year for this license compared to $99 per year
> for the iOS Developer License. A given device can have apps installed
> from only one iOS Enterprise License at a time.
>
> Apps may be deployed on Devices in two ways: (1) deployment for
> internal use by Employees, and (2) deployment for use by Customers
> either on Your physical premises or under the direct supervision and
> physical control of Your Employees in other locations, subject to
> Apple’s right to review and approve such deployment as set forth
> herein.”

**Pro’s**

  * The App Store approval process is not required.

  * The general public cannot see a listing for your app, purchase or
    install it. It is not on the App Store.

**Con’s**

  * The Enterprise program is intended for employees and contractors of
    the licensee only.

  * The licensee is responsible for distributing and updating the app.
    This can be done manually by email, making the app available on an
    Intranet site, through a [Mobile Device Management
    System (MDM)](http://en.wikipedia.org/wiki/Mobile_device_management), etc.

  * The cost is $299 per year for the Enterprise Developer Account
    compared to $99 per year for the iOS Developer Account.

## 3.Custom B2B Apps Program

> Apple has programs for volume purchasing and custom B2B apps. These
> programs operate from the online [Business
> Store](https://vpp.itunes.apple.com/us/store). The Volume Purchasing
> Program allows businesses to buy apps from the public App Store in
> bulk. Custom B2B Apps extend the Volume Purchase Program for custom
> B2B apps built by third-party developers. The third-party developer
> determines which Volume Purchase customer(s) can purchase a given app.
> Such apps are not available on the public App Store but only through
> the Business Store.

**Pro’s**

  * More convenient for larger distributions. Each individual
    installation does not require a user to make a purchase through the
    public app store and expense the cost. Instead, users are given a
    coupon that they can use to install the app.

  * Apple provides the distribution service – the Business Store. This
    provides some features of an MDM.

  * The general public cannot see the listing, purchase or install
    the app.

**Con’s**

  * Requires App Store approval process for initial app and updates.

  * If you charge a price for the app, 30% of the revenue goes to Apple.

  * B2B apps are only available to businesses enrolled in the Volume
    Purchase Program. [The Volume Purchase Program is limited to 10
    countries as of May,
    2013](http://www.apple.com/business/vpp/): Australia, Canada,
    France, Germany, Italy, Japan, New Zealand, Spain, United Kingdom,
    and United States

> \*Note: An iOS Developer License is required to use the Custom B2B
> Apps Program. Limiting an app to the B2B App Store is an option when
> submitting to the Public App Store.

 

## 4.Ad Hoc Distribution (intended for Testing)

> Ad Hoc Distribution allows you to distribute apps to up to 100 iOS
> devices for testing. You must register these devices manually by their
> ID. Devices can be removed/replaced once each membership year). Ad Hoc
> Distribution is a feature of both the iOS Developer Program and the
> iOS Developer Enterprise Program. This may be all that is needed for a
> prototype or trade show.

**Pro’s**

  * The App Store approval process is not required.

  * The general public cannot see the listing, purchase or install
    the app.

  * Over-the-air installation from a hyperlink (hosted on your web
    server or on an iOS Beta Testing Service \*mentioned next) or by
    emailing to a computer with iTunes installed (and then installing to
    the device).

**Con’s**

  * Limited to 100 devices (devices can be removed/replaced once each
    membership year).

  * The UDID (Unique Device IDentifier ) of each device must be
    associated with your provisioning profile. This is a manual process.

  * Your team must manage deployments and updates.

  * The related developer provisioning profile expires in one year. This
    means that the app will run on a given device for a maximum of
    one year. When the Developer Provisioning profile expires the app
    will need to be rebuilt with a new provisioning profile.

 

## 5.iOS Beta Testing Service: 

### A.TestFlight

> TestFlight is a free over-the-air platform used to distribute beta and
> internal iOS applications to team members. Developers can manage
> testing and receive feedback from their team with TestFlight’s
> Dashboard.
>
> TestFlight makes use of your iOS Enterprise License or Developer
> License to create Enterprise and Ad Hoc provisioned apps.

-   Other Testing Tools and Services

    [Hockey App](http://www.hockeyapp.net/): Beta and release deployment
    of Mac OS X , iOS (beta only) and Android.

    [HockeyKit](https://github.com/TheRealKerni/HockeyKit): Open source
    project for hosting beta versions on your own PHP5 server.

    [Apphance](http://www.apphance.com/): Deployment on iOS, Android,
    Windows Phone, Nook and Kindle.

# V.TESTFLIGHT

**Popularity:** If you’re into the Apple development world, you have
probably heard of TestFlight. TestFlight is an online service for
over-the-air installation and testing of mobile applications, currently
owned by Apple and only offered to developers within the iOS Developer
Program.

Developers signed up with the service to distribute applications to
internal or external beta testers, who could subsequently send feedback
about the application to developers. The TestFlight SDK additionally
allowed developers to receive remote logs, crash reports and tester
feedback.

**Platforms:** iOS, watchOS, and tvOS.

**API & Integrations:** [Fastlane](https://fastlane.tools/), it integrates well 
when delivering your app to TestFlight’s beta testers.
With a single command line, you’re able to get your app from development
to your beta testers’ hands.

**Ease of Use:** If you’re not using an automation tool like Fastlane in
order to automate your workspace, it’s still pretty straightforward to
get your app into beta testing. The whole process is done through the
iTunes Connect portal, and you can add either Internal or External
Testers. Internal testers are “part” of your development team, thus only
the ones that are currently assigned as developers or have developer
roles in your iTunes Connect team (like admins). The app distribution
sent to internal testers are the fastest since they don’t require a Beta
App Review nor comply with the App Store Review Guidelines, like the
distribution sent to external testers. 

On the other hand, to invite external testers, who is anyone that’s not
in your development team, you only need their email address and they’re
good to go once they’ve accepted the invitation. Only TestFlight has
this Internal and External Tester concept.

TestFlight’s advantage is that it doesn’t require the developer to
handle the provisioning profiles for new devices manually, so that
improves its ease of use considerably.

**Setup Time & Effort:** The setup time is mostly creating the app
in the iTunes Connect and submitting the app via Xcode, which could take
up to a few minutes to get your app approved through Apple’s automated
app revision system. You need to explicitly declare some information
about the test build you’re submitting, like a description and what
needs to be tested, so that might take a little longer than if it didn’t
require that info.

**Misc Pros:** Every tester needs to download Apple’s official
TestFlight app in the App Store in order to be able to download and test
app distributions. Another great feature is that you can assign notes
and details to the app being distributed so the testers can see what
needs to be tested.

Basic information about crashes and sessions are stored in TestFlight
Data so the developers may track what’s going on with each of the
versions that are being tested. Extra feedback may be sent to the
developers via email (within TestFlight app) alongside a log with
information of the current device.

**Misc Cons:** What bothers the developers the most is the Beta App
Review that is required in order to invite external testers (most times
the most important testers are outside of our development team). So
that, and the fact that it doesn’t support non-Apple platforms, are the
reasons why many people complain about TestFlight. Other than that, it’s
a great tool, it was already one of the most popular (if not the most)
on the market before Apple bought it, and it definitely became even more
popular after its acquisition.

**Pricing:** Apple’s official solution to beta distribution is
completely free to use. 

# VI.HOCKEY APP

**Popularity and Misc Pros:** More complete than TestFlight, and
definitely among the most popular beta distribution services out there,
Microsoft’s solution to beta distributions also offers user feedback
right from the app, insights of how users are using the app,
sophisticated team management features, and is well-suited for large
companies that develop many different apps. 

**Platforms:** It also supports a greater range of platforms, from
Android, iOS, macOS and Windows, to Cordova, React Native, Unity, and
Xamarin. 

**Ease of Use and Setup Time & Effort:** The setup is pretty much the
same as Fabric, which I’ll be covering later on. There are numerous ways
to add the HockeyApp SDK to your project, including CocoaPods, Carthage,
and manually. Uploading a new build may be done via the web dashboard or
via HockeyApp for Mac, and is really straightforward.

**Integrations & APIs:** It features [a huge range of integrations and
bug
trackers](https://support.hockeyapp.net/kb/third-party-bug-trackers-services-and-webhooks/supported-bug-trackers),
and provide[ handy
tutorials](https://support.hockeyapp.net/kb/third-party-bug-trackers-services-and-webhooks)for
the most popular ones
like [JIRA](https://support.hockeyapp.net/kb/third-party-bug-trackers-services-and-webhooks/how-to-set-up-a-webhook-in-jira), [Slack](https://support.hockeyapp.net/kb/third-party-bug-trackers-services-and-webhooks/how-to-use-hockeyapp-with-slack), [GitHub](https://support.hockeyapp.net/kb/third-party-bug-trackers-services-and-webhooks/how-to-set-up-a-webhook-in-github), [Status
Board iPad
app](https://support.hockeyapp.net/kb/third-party-bug-trackers-services-and-webhooks/how-to-use-hockeyapp-with-status-board), [Microsoft’s
Visual Studio Team
Services](https://support.hockeyapp.net/kb/third-party-bug-trackers-services-and-webhooks/how-to-use-hockeyapp-with-visual-studio-team-services-vsts-or-team-foundation-server-tfs),
 and
also [webhooks](https://support.hockeyapp.net/kb/third-party-bug-trackers-services-and-webhooks/how-to-use-hockeyapp-webhooks).
Additionally, HockeyApp also supports various build servers & tools:
Fastlane, Jenkins, Travis CI, and Visual Studio Team Services.

**Pricing:** All this is available in a free tier for up to 2 apps, and
the other plans can be found [here](https://www.hockeyapp.net/pricing/).
For those looking to use more than 2 apps and wouldn’t like to pay more
for it, HockeyKit open source might be an alternative.

# VII.MAAS360 - Introduction

MaaS360 Mobile Application Management simplifes mobile application
management by delivering an easy-to- use enterprise app catalog with
robust security and operational lifecycle management of apps.

**Enterprise application catalog**

An intuitive, customizable enterprise app catalog for iOS, Android and
Windows Phone.

**Mobile application lifecycle management**

A platform to distribute, update, manage and protect both public and
enterprise mobile apps.

**MaaS360 Mobile Application Security**

A mobile application container for enterprise apps with built-in
security management as an optional add-on to MaaS360 Mobile Application
Management.

**Mobile application compliance and enforcement**

Security policies to blacklist, whitelist and require apps. Automated
enforcement rules to alert administrators, block email, restrict network
resources and perform remote wipes.

**IBM ® MaaS360 ® Content Service**

An option to host and distribute your enterprise mobile apps on a
globally optimized app distribution network.

**Volume purchase program**

Support for bulk app licenses for employees.

# Appendix

-   Apple Developer Site

    <https://developer.apple.com/library/content/documentation/IDEs/Conceptual/AppDistributionGuide/TestingYouriOSApp/TestingYouriOSApp.html>

    <https://developer.apple.com/programs/>

-   [Comparison of iOS Developer
    Programs](https://developer.apple.com/programs/start/ios/): iOS
    Developer Program ($99/year), iOS

-   Developer Enterprise Program ($299/year), iOS Developer University
    Program (Free)

-   [Distributing Enterprise Apps for iOS
    Devices](https://developer.apple.com/library/ios/#featuredarticles/FA_Wireless_Enterprise_App_Distribution/Introduction/Introduction.html)

-   [Create Custom B2B Apps for Sale to Your Customers Enrolled in the
    Volume Purchase Program](http://www.apple.com/business/vpp/)

-   [Business Store](https://vpp.itunes.apple.com/us/store)

-   [TestFlight](https://testflightapp.com/)

-   [Building and Distributing Custom B2B Apps for
    iOS](https://developer.apple.com/videos/wwdc/2012/) WWDC 2012 Video
    (requires Apple Developer account)


