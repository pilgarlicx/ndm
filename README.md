![github-banner.png](http://i.imgur.com/ZxOCrmo.png)
[![Download ndm](http://i.imgur.com/z68cq3y.png)](https://github.com/720kb/ndm/releases/download/0.0.1/ndm-0.0.1.dmg)

###What is this ?

**ndm** formally _"npm desktop manager"_ is the client GUI for npm (MacOSX only for the moment).

With **ndm** you can easily manage npm and npm packages directly from the couch, without any worries.

It is based on the [npm-cli](https://docs.npmjs.com/cli/npm) and developed over [electron](https://github.com/electron/electron) with some touch of AngularJS and Sass.

Feel free to reach any of us for any info/question, or to support the project in any way you wish.

###I love the Shell, why use an app?

Of course, we all love it too.

The Shell is obviously very powerful.

However: not all the people know how to use it from the scratch.
Sometimes and very often, they can not use the Command line for intern/office/job reasons, or they are not willing to use it at all.

Forget not that: using ndm, does not mean you can no longer use the Command line and viceversa.

###Installation

Download the executable for your OS at this link: [DOWNLOAD](https://github.com/720kb/ndm/releases/)

###Develop

_Setup_

`$ git clone <repo> && cd ndm`

`$ npm install`

_Run app_

`$ npm start`


###Build

If you want to make your own executable:

`$ git clone <repo> && cd ndm`

`$ npm install`

Adjust `package.json` file [build](https://github.com/720kb/ndm/blob/master/package.json#L20) section to your needs, then run:

`$ npm run build`


###Contribute

We'll be much grateful if you help and contribute to the project, in any way you can or wish.
Feel free to contribute by forking, opening issues, pull requests and whatever you think it's important for the project.

Doors are wide open!

###License

GNU GPLv3 [License](LICENSE.md).

###FAQ
**_Is ndm stable?_**

The first releases are not guaranteed to be very stable, some problem/bug may happen.

Just give it time, have some patience and, if you would, please contribute by forking, PR and/or creating issues, your help is always appreciated.

**_Do i have to worry about anything when using ndm?_**

Actually not, not really.
ndm does not run any malicious or env/system breaking commands in background, and it doesn't run anything outside npm native commands.
If you want to be 100% sure about this, just look at the source code, which is clear and very readable.

**_Why is so slow on my pc?_**

ndm speed depends exclusively on your pc/device specs and [npm-cli](https://docs.npmjs.com/cli/npm) speed.
We can't do much to speed up your computer or the npm commands.

**_Why Mac only?_**

We now focus on one OS but the app is developed keeping in mind that it will have to run also on other OSes. We won't _put too much meat on bbq_ for the moment, it is now very important to obtain an OS-abstracted and stable app.

As soon as we are sure that the project is stable, it will be delivered to the other OSes.

**_Yarn?_**

Yarn is a great tool: we will be looking forward to see what happens, said that, if you have any idea or suggestion: you're welcome!

**_Support?_**

Just open an issue we'll be in touch.

###Who we are

[720kb](https://720kb.net)
