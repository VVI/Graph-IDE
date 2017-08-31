

## Synopsis

To gain access to this private repository please email support@vvi.com This repository contains files to build Graph IDE for iPad, Mac and Windows.

## Motivation

You can link in your own source code files and then use methods in those files as callbacks to automate data importing. You may also incorporate customizations onto the inspector editors, including factory editors.

## Installation

You must first have [Graph Builder](http://www.vvidget.org/graph/ "Graph Builder") on your Mac. That is not only for licensing issues but also because most of Graph IDE and all of its customization is implemented via Graph Builder documents which are essentially configuration states to inspectors, including the factory inspectors where you can add your own data importing instantiation objects. In another lingo: Graph Builder permits you to re-skin this app.

For the precompiled product (target) see: [Graph IDE On App Store](https://itunes.apple.com/us/app/graph-ide/id904733611?mt=8 "Graph IDE On App Store"). The product is the actual Graph IDE application.

## Design

Graph IDE is designed to be as codeless as possible. It does that via document (template) states that are part of the Graph IDE interface. Since no preconceived state is complete (it is finite), Graph IDE includes a code parser and state execution engine (some call it a compiler) to extend its functionality. Whereas a normal IDE is file based, Graph IDE is object based and the execution is determined by objects initiated on its documents.

## Documentation

Please see: [Graph Builder Manual](http://www.vvidget.org/manuals/GraphIDE/ "Graph IDE Manual") for documentation on making, editing and programming templates.

## Build and Run

This project is designed to build using Xcode 8 and run in the Xcode simulator for iOS 10. It will probably build out of the box when you check it out, however there may be site-specific issues such as provisioning profiles and certificates. It will operate in demonstration mode until it is properly licensed. For support please email [support@vvi.com](mailto:support@vvi.com "Mail Support").

## Help And Support

You are free to learn at your own pace by checking this project out and modifying it. You may also wish to commit some additional factory objects to this project. If you have questions and require more support then please email [support@vvi.com](mailto:support@vvi.com "Mail Support").

## Dependencies

This project relies upon the Vvidget and FFI libraries which are included in this project as archive files.

## License

(c) Copyright 1991-2017, VVimaging, Inc. (VVI). All Rights Reserved.

Use of this software is governed by the END-USER LICENSE AGREEMENT FOR VVI SOFTWARE.

Redistribution is subject to the VVIDGET LIBRARY LIMITED REDISTRIBUTION LICENSE AGREEMENT which requires a valid written and signed Purchase Agreement for the "Vvidget Library Redistribution" product executed by an authorized representative of VVI. This software is protected by copyright and licenses restricting use, copying, distribution, and decompilation.

The Graph Builder EULA gives you the rights to use this project on your computer in the simulator in a manner consistent with the EULA. If you wish to deploy the product (target) to another computer (including an iPad) then you must have a redistribution license agreement. Please contact [sales@vvi.com](mailto:sales@vvi.com "Mail Sales") for that purpose.

For license questions please email [sales@vvi.com](mailto:sales@vvi.com "Mail Sales").
