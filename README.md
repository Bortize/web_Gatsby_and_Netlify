# web_Gatsby_and_Netlify
Install a website with Gatsby and Netlify for free

First of all, the first thing you should check is that you have the following components installed in your terminal

**Homebrew**

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"`

**Xcode**

`xcode-select --install`
acept the license --> `sudo xcodebuild -license accept`

**Node**

`brew install node`

update node version

`brew install node`

**Git**

`brew install git`

**Npm**

`npm install -g npm`




2. The next thing you do is install Gatsby. Before installing, make sure you have it installed by typing the following command in terminal

`npx gatsby --help`

* A message may appear informing you to upgrade to a new version

To start using Gatsby, you just have to clone some of their templates that they offer on their websites. You should do it with the following command

`gatsby new hello world https://github.com/gatsby/gastby-starter-hello-world`

**Error 11615** this error occurs when you are trying to create a project that already exists.

**Error** An error may occur when you create an error indicating that we must upgrade to a new version.


4. You must display the site

`npm run develop`

5. Check that everything works correctly. access **localhost:8000** and if we have followed the steps correctly the web will appear.
To start making modifications you must access the installation folder with visual studio code.

////////////////////////////////////////////////////////////////////////////////////////////////////////

 **NETLIFY**
 
1. Create a new repository in GitHub
2. Clone the repository on your Mac
3. Put the files generated in port 3 into the repository
4. Push

2.1 Create Netlify account
2.2 go to sites and click on New git site
2.3 choose in continuous display the version control system you have chosen
