# TApiModule
TApi is a PowerShell wrapper for the Tronscan API, designed to help Windows professionals adopt the blockchain.
With the TApi module you will be able to automate many blockchain interactions, including performing Airdrops.
Until now there has largely been no project publicly available that allows anyone to automate day to day tasks, short of creating thir own scripts.  All references (and there are few) to scripting for the API are all in perl or python.  
I wanted to expand out to the native Windows platform, further encouraging mass adoption of blockchain technologies.

I have created a very simple menu driven interface to help the less tech savvy people out there, perform some common tasks.
If there is enough demand for it, I will create a WPF GUI for it in the future.

Using the TApi Menu, you can search for specific addresses, blocks, tranactions etc and displaying them in a spreadsheet for filtering, and refining, directly within the TApi Menu.
You can list all the exhanges that trade TRX, find out the price, trading pairs and ranks.
Get your wallet details, including the balances, received and sent transactions.
Send to an idividual or perform an Airdrop of TRX or any specified token.

If you do not wish to use the TApi Menu, you have full access the TApi module to build your own scripts in PowerShell.  Heard over to the Wiki for details to get you started.

# Important
It is highly recommended that you download and install the Tronscan API and run it locally so you do not send your private key over the internet.  Head over to https://github.com/tronscan/tronscan-docker and download Rovaks docker compose instance of Tronscan.

# Prerequisites
The TApi Module should work with PowerShell 3 and above, however it has only been tested on PowerShell 5 at this stage.
If you are using the TApi Menu, some features will require the Window Presentation Core and Framework in order to display correctly.

# Intallation
The TApi module can be run from anywhere or installed in your PowerShell profile.  
In order for everthing thing to play nicely, it is recommeded that you keep the Config and TApi Menu scripts in the same folder.

# Authers
* Jaysn Rye -Initial Build

# Acknowledgements
Rovak for his great work and providing us with the docker image of the Tronscan API. https://github.com/Rovak
