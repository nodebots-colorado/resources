# UP AND RUNNING SOFTWARE FOR NODEBOTS

#### DESCRIPTION

This is intended to be a simple resource for getting everything up an running on your machine. Feel free to skip a step if you already have something installed.

## ASSUMPTIONS

We're assuming that you are already _somewhat_ comfortable with working in the terminal and that you have a code editor installed. If you don't have a code editor installed _and you would like one_, we would recommend either [Sublime](http://www.sublimetext.com/3) or [Atom]("https://atom.io"). Both are free and quality editors.

## WHAT WE'LL BE INSTALLING
- NodeJS and NPM
- Johnny-Five
- Arduino IDE

## INSTALLING NODE AND NPM

#### MAC OS

**VIA HOMEBREW**

If you have [Xcode tools]("https://itunes.apple.com/us/app/xcode/id497799835?mt=12") and  [homebrew]("http://brew.sh") already installed, probably the easiest way to install Node is `brew install node`.
NPM, _or Node Package Manager_ comes with the installation, so you're done! Verify by typing `node -v` in your terminal. If you get a version as a response, you're good to go. You can also verify NPM is installed by typing `npm -v`.

**FROM NODE**

Otherwise you can download from [Node's site](https://nodejs.org). And NPM comes installed with it. Verify by typing `node -v` in your terminal. If you get a version as a response, you're good to go. You can also verify NPM is installed by typing `npm -v`.

#### WINDOWS

As reccommended by NPM for Windows users, download node from [Node's site](https://nodejs.org). NPM comes installed with Node. You can verify by typing `node -v` in your terminal. If you get a version as a response, you're good to go. You can also verify NPM is installed by typing `npm -v`.

#### LINUX

If you're running on Linux, it's recommended that you install the latest binaries compatible with your system. You can find them [here]("https://github.com/nodesource/distributions"). You can verify by typing `node -v` in your terminal. If you get a version as a response, you're good to go. You can also verify NPM is installed by typing `npm -v`.

## INSTALLING JOHNNY-FIVE
Once you have Node and NPM set up, installing Johnny-Five is as easy as `npm install johnny-five` in your terminal. You might need to run `sudo npm install johnny-five` and enter a password if you have issues with permissions.

## INSTALLING THE ARDUINO IDE
You'll also need the Arduino IDE, which you can download [here]("http://www.arduino.cc/en/main/software"). You will then want to plug in your Arduino and open the Arduino IDE.

Open File > Examples > Firmata > StandardFirmata

Then click the upload button. If it was successful, you can then close the IDE.

## CLOSING
You're all done! The next step is playing with the hardware!
