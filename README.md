# Kalibrr Design System

The Kalibrr Design System used by the Kalibrr Job Platform and other Products.

## Getting Started

Make sure to have git, nodejs and sass installed on your machines.

### Prerequisites

#### Installing Git

For Macs install Xcode Command Line Tools. Try running git from the terminal to make sure you have it.

```
git --version
```
#### Installing NodeJs and NPM

You can download the macOS Installer directly from the [nodejs.org](https://nodejs.org/en/) which will include npm.

You can also install it through homebrew via terminal
```
brew install node
``` 

#### Installing Sass

After installing NodeJS you can run
```
sudo npm install -g sass
```

#### Installing Gulp CLI
```
npm install --global gulp-cli
```

### Installing

Go to your projects folder and run the following in terminal
```
Git clone git@git-ssh.kalibrr.com:kalibrr/design-system.git
```

This should download the git repository into your local machine. Then move to the downloaded git repository folder
```
cd design-system
```

After that run npm install
```
sudo npm install
```

## Test the install

Run gulp from within the design-system folder
```
gulp
```

This should open a browser with a live view of the design system pages.

## Other Resources
### A Sketch Library
A Sketch library has been created to help with designing full pages and for designers who are more comfortable working with Sketch than with code. You can request access to the Kalibrr Design System Sketch Library by creating a Sketch Cloud account and requesting it from the link below

[Kalibrr Design System Sketch Library](https://sketch.cloud/s/pQPEJ)

## Troubleshooting
If you're having trouble feel free to email the kalibrr design team at design@kalibrr.com


### Authentication Problems
If you're having trouble and getting authentication problems in terminal, make sure you've done one of the following.

#### If you're trying to clone through ssh 
If you are git cloning from this url
```
git@git-ssh.kalibrr.com:kalibrr/design-system.git
```
Make sure that you've generated an SSH key and added it to your profile. You can add an SSH key in [this page](https://git.kalibrr.com/profile/keys) as well as follow instructions in a tutorial mentioned there.

#### If you're trying to clone through an http/https
If you are git cloning from this url
```
https://git.kalibrr.com/kalibrr/design-system.git
```
Make sure you've set access token through [this page](https://git.kalibrr.com/profile/personal_access_tokens)

Instead of entering your git password, use the access token name as your git password.

## Kalibrr Design Team
* Mark Lester Coscolluela Lacsamana
* Alex Hans Collado
* Ferdenee Joi Mempin

