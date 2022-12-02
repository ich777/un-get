# un-get for unRAID

un-get is a simple command line tool to install packages from Slackware to unRAID.

Start by issuing: `un-get --help` in a unRAID Terminal to get available commands and how to use this tool.

**Please Note:** un-get allows only installation of packages which are not already installed on your system and only allows removing packages which are installed by un-get!

**Other Repositories:** You can also add other repositories which follow the Slackware standard, even if it's hosted on GitHub like: https://github.com/ich777/slackware

**REPORTING BUGS/ISSUES:**
If you find a bug or have some kind of issue with un-get please use the issue tracker here on GitHub.

**DISCLAIMER**
- This tool will maybe never make it to the CA App because it is meant for advanced users only
- Use this only if you really, really, really need some additional package on unRAID  
(I would always recommend that you use Docker containers, LXC containers or VMs instead of running it on bare metal)
- This tool is currently in development but should get the job just done fine

**INSTALLATION**
- In the Unraid web UI, go to "Plugins", then "Install Plugin"
- Paste `https://raw.githubusercontent.com/ich777/un-get/master/un-get.plg` into the text field that is labelled "Enter URL of remote plugin file or local plugin file"
- Click "Install"
