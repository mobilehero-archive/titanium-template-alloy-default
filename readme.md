# Titanium Alloy Template (Default)

> This template is based on the new project that is created when using the Titanium Mobile CLI tool, with some modifications (see below)

## Usage

1. Install `[Geek Mobile Toolkit](https://www.npmjs.com/package/@geek/mobile)`

```
npm install -g @geek/mobile
```

2. Create new mobile project

```
mobile app:create [NAME] [TEMPLATE]
```

> If you omit `template` parameter, this template (`@titanium/template-alloy-default`) will be used.

```
mobile app:create my-new-app
```


## Current Features

* Titanium SDK 7.5.1.GA
* Updated .gitignore file
* Modifications to `tiapp.xml`:
  * Added the following iOS permissions:
    * Camera
    * Photo Library
    * Micriophone
    * Apple Music
    * Wifi
  * Added iOS query schemes
  * Added iOS bundle url types
  * Disabled Appc Analytics
  * ESLint - Code Linting
  

## Roadmap

  * More updates

## Other Projects

* [Geek Mobile Toolkit](https://www.npmjs.com/package/@geek/mobile) - Toolkit for creating, building, and managing mobile app projects.
* [Titanium Alloy Template (Basic)](https://www.npmjs.com/package/@titanium/template-alloy-basic) - Basic Alloy app.  What you get when creating new app project with Titanium CLI.

----------------------------------
Stuff our legal folk make us say:

Appcelerator, Appcelerator Titanium and associated marks and logos are 
trademarks of Appcelerator, Inc. 

Titanium is Copyright (c) 2008-2019 by Appcelerator, Inc. All Rights Reserved.

Titanium is licensed under the Apache Public License (Version 2). Please
see the the Titanium license file for the full license.

