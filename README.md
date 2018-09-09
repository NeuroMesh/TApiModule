# TApi (Alpha Release)
![TApi Logo](/Tron%20flame%20hands%20no%20branding.png)
TApi is a PowerShell wrapper for the Tronscan API, designed to help Windows professionals adopt the blockchain.
With the TApi module you will be able to automate many blockchain interactions, including performing Airdrops, getting a list of voters for the last round, converting between epoch/local time, sun/trx and much more.  
The TApi module enables you to create your own PowerShell scripts to do whatever you like. 

Until now there hasn't been any publicly available projects that allow you to automate day to day tasks in a Windows environment.  All references (and there are very few) to scripting for the API are all in Perl or python.  
I wanted to expand out to the native Windows platform, further encouraging mass adoption of blockchain technologies.

I have created a very simple menu driven interface to help the less tech savvy people out there, perform some common tasks.
If there is enough demand for it, I will create a WPF GUI for it in the future.  Just keep in mind that the TApi Menu is just a small example of what can be accomplished with TApi and is provided mainly as an example.  In saying that, it is a fully functioning tool at your disposal.

Using the TApi Menu, you can:
* Search for specific addresses, blocks, transactions etc and display them in a spreadsheet for filtering, and refining, directly within the TApi Menu.
* List all the exchanges that trade TRX, find out the price, trading pairs and ranks.
* Get your wallet details, including the balances, received and sent transactions.
* Send to an individual or perform an Airdrop of TRX or any specified token.
* Get a list of everyone who has voted for you this round and kick off an airdrop

If you do not wish to use the TApi Menu, you have full access the TApi module to build your own tools.  Heard over to the Wiki for details to get you started.

## Important
It is highly recommended that you download and install the Tronscan API and run it locally, so you don't send your private key over the internet.  
Head over to this [Article](https://www.neuromesh.me/blog/windows-guide-to-installing-tronscan-api-in-docker) on my blog to get started.
TApi stores your private key in an encrypted string in the Windows registry and can only be decrypted by the account that created it.  If you have multiple users on the same machine, TApi will create a new key in the registry for each user to ensure that no one else can gain access to your own personal settings.

### Guides 
* [Quick Start Guide](https://github.com/NeuroMesh/TApiModule/wiki/Quick-Reference)
* [Cmdlet Reference](https://github.com/NeuroMesh/TApiModule/wiki/Cmdlet-Reference-Guide)

### Pipeline
If there is enough support for the TApi project, I'll be looking at implementing some new features and improvements
* Store all transactions in a SQL database (currently stored in a CSV file)
* Create a proper GUI interface that implements TApi
* Add support for new API calls as they come out
* Any other suggestions you may have

### How can I contribute to the project
Currently looking testers, both SR's and not.  If you have experience with the blockchain and beta testing, get in contact via one of my contact methods below.

Found an issue?
*   [Raise a new issue](https://github.com/NeuroMesh/TApiModule/issues)

Want to fix an issue?
*   Clone the project and submit a pull request

### Keep up to date
*   [Visit my blog](https://neuromesh.me)
*   [Follow me on twitter](Cmdlet-Reference-Guide)![](http://twitter.com/favicon.ico)
*   [Reach me on Telegram](https://t.me/NeuroMesh)
*   [info@neuromesh.me](info@neuromesh.me)

## Authors
* Jaysn Rye -Initial Build

## Acknowledgements
* Rovak for his great work and providing us with the docker image of the Tronscan API. https://github.com/Rovak
* Tron-Europe for always being happy to assist with any questions I've had along the way  https://www.tron-europe.org/

## Disclaimer
Please take the time to review the code before using the tool.  It is currently in alpha and may have bugs.  I will not be liable for any loss or damages as a result of use of this tool.
