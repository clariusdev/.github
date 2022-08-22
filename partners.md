Partners
========

Clarius is excited to be working with multiple partners that are bringing new technologies into the healthcare space that require ultrasound imaging for real-time guidance and other novel clinical solutions.

Working with Clarius scanners is extremely simple, and leveraging our suite of APIs through our **Clarius SDK** program allows partners to build elegant solutions that work directly with Clarius' existing ecosystem, or to build an entirely standalone solution.

We offer multiple tools, many of which were previously developed for the research community, or for those building prototype solutions for taking to market in the future. Through two new initiatives, we now offer dedicated pathways for go-to-market solutions:
1. OEM Partnerships
2. Clarius Marketplace

OEM Partnerships
================

Those wishing to develop completely standalone solutions can work with Clarius and enter into an OEM partnership that will allow a 3rd party to purchase and deploy Clarius scanners on their own technology platform to their own customers. Some eligbility requirements for becoming an OEM partner include:
* Minimum yearly purchase of scanners
* Paying a nominal yearly fee per scanner (the oem license)
* Paying a yearly support fee for training, support, and any custom development required

From the technology standpoint, partners can develop and deploy in any means they wish, however we have built the dedicated [Solum API](https://github.com/clariusdev/oem) for creating standalone software and Apps. Developers are encouraged to build a full ecosystems for their customers with potential to use cloud, implement custom analysis and reporting, and build in proper security measures.

Solum is available for deployment on the following platforms:
 * Windows
 * Linux
 * iOS
 * Android

Clarius Marketplace
===================

The marketplace has been developed for partners to go to market with a new technology, typically using artificial intelligence and machine learning, without having to invest heavily into a fully custom solution or dedicated sales and marketing pathway. By leveraging the Clarius customer install base, the marketplace will automatically target users that may have interest in using novel AI or workflow solutions to augment the existing use of their Clarius scanner.

The marketplace will be available to Clarius customers that have signed up to our products through the membership pathway that offers additional features and solutions through a yearly fee, and purchasing of marketplace Apps will be conducted in the same format.

Some highlights for the marketplace technologies:
* Clarius will manage the marketing, sales, billing (yearly), and licensing of the partner App
* Partner can set the yearly price for their solution
* Clarius will retain 30% of the sale
* A minimum trial period must be offered to customers
* Apps that do not yet have regulatory clearances, but will require them based on the indications for use, may be subject to a free trial indefinitely, and must be clearly labelled at all times in the App interface, until such clearances are obtained

From the technology standpoint, partners must develop and deploy an App on Apple's App Store and Google's Play Store. The development must make use of the [Cast API](https://github.com/clariusdev/cast), which allows a direct connection to the Clarius scanner for obtaining real-time images and other parameters. The Clarius App must also be running, thus user workflow would be as follows:
* Start Clarius to initiate and perform scan
* Launch 3rd party App within the Clarius App when required
* Run Apps side-by-side (iPadOS or Android), or background the Clarius App (Android only) to image with the partner App to obtain AI feedback and results

App restrictions:
* Users must **not** be required to sign-in to a cloud or other user management system to begin, however cloud can be offered as an optional feature
* Apps must be able to process images in real-time for immediate feedback - suggest making use of [TF Lite](https://www.tensorflow.org/lite)
* For Apple devices, only iPads can be used, which offer the split screen functionality, since Apple does not provide a proper IPC technology on iOS, and iPhones do not allow Apps to run anything significant while in the backgroud
* Since most connections to the Clarius scanner use the probe's Wi-Fi, there is no guarantee internet is required, therefore, for real-time usage, internet access must **not** be required
