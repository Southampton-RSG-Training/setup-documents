## Git Setup ##

### Windows
We'll be using Git Bash for both git and a shell to run it in. If you've already installed Git Bash then go to the next section. Otherwise, go to [git for windows](https://gitforwindows.org/) and click **Download**, then install it following the instructions in the section above.


#### Mac OS
To use Git you must install the Apple Command Line Tools, this may take a few minutes.  

You can obtain these [from Apple](https://developer.apple.com/download/more/?name=command%20line%20tools%20for%20xcode%2012) (requires your Apple ID)

- Select **Command Line Tools for Xcode 12 (or higher)** and click the link to download the dmg archive.
- If prompted, choose to allow downloads from developer.apple.com
- Open the downloaded dmg archive from the Downloads folder
- Double-click the Command Line Tools.pkg icon to install

Alternatively, you can install the tools from the command line:

~~~
$ xcode-select --install
~~~
{: .language-bash}

#### Linux
Git comes pre-installed on most Linux distributions. You can test if it's installed by running `git --version`. 
If it's not installed, you can install it by running `sudo apt-get install git` or `sudo yum install git`, depending on 
your distribution.
