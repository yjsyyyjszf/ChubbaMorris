# ChubbaMorris

REAL ESTATE & AGENCIES, PROPERTY MANAGEMENT, COMMUNITY HOUSING, CONVEYANCING, SOLICITORS & LAND TITLE REGISTRIES

Uses Elastos ELA "blockchain+" system.
ELA tokens (fractional) partly as price of transactions,
predominantly as general digital currency.
"Merge mined" by Bitcoin miners.
Truly distributed ledger. Cloud servers are only involved for mass storage of documents, images, audio, video and as part of the developing Elastos IPFS blockchain support system for mass usage data intensive systems like ours.
Secure Elastos.RT Runtime for the client,
and secure Elastos Carrier network for the internet.
Employs the open and adaptable standard Component Assembly Runtime (CAR) framework.
The CAR framework establishes links between components/devices, flexibly across operating systems.
Trust is embedded by distributing ledgers ..  Each appropriately authorised participant in a transaction has a key to their copy of the record.  Only appropriate information, particularly in Multi-Party Transactions, is available to Participants.

The mechanism of the Blockchain ensures faithful and verifiable copies of every transaction.  
The Bitcoin Blockchain mining process 'underwrites' the Elastos Blockchain's trust mechanism.  
Your transactions are 'mined' in order to validate and seal them.

Chubba Morris(TM) conceived by John Olsen IT Cloud Solutions Australia with assistance from Carsten Eckelmann, 2pisoftware and Susan Dart, Melbourne Blockchain Centre.

ref.  https://www.cyberrepublic.org/project-detail/5b7fc07547f7f618e0d01f39 


Also, look around the elastos github site.  https://github.com/elastos

Then START:
 https://github.com/elastos/Elastos.ELA  https://github.com/elastos/Elastos.ELA.Client 
 
 https://github.com/elastos/Elastos.ELA.SideChain  https://github.com/elastos/Elastos.ELA.Client.SideChain
 
  https://github.com/elastos/Elastos.RT/blob/master/Docs/getting_started.md   https://github.com/elastos/Elastos.RT/blob/master/Docs/How_to_build_CAR_tools_such_as_carc.md
  https://github.com/elastos/Elastos.RT/blob/master/Docs/How_To_Write_A_Car_Component.md
  
  A lot of the first series of tasks (ie getting blockchains and clients working - clients carry ability to create and list etc wallets, thus connecting to main and side chains - and the DID Chain) is from a general page collecting a lot of stuff including Trinity Browser ie:  https://github.com/elastos/Elastos .
  
  Trinity Browser is the easiest system to use to develop an interface to a sidechain as far as providing the GUI and access to the DApp's user services (Blockchain/Database/Backend).
  
if you follow the initial instructions after installing all the software (suggest creating a base version of Ubuntu 16.04 on Oracle's Virtual Box, with the software installed and car compiler built and deployed) and then when you are happy that everything is working (there will be an error on sidechain from SPV not having TLS security you can ignore) you should shut this down and clone it as a machine to work on and destroy readily.

Anytime you get further advanced in a permanent way shut down the machine with saved state and clone it freshly.

 Sample of how to run a CAR program:  https://github.com/elastos/Elastos.RT/blob/master/Docs/How_to_run_test_on_ubuntu.md
 
 The work of coding the database in C++ has been done with the exception of correcting all typoes and coding the main() method and utility methods.
 
 .  Method of deployment of this blockchain based database to the sidechain is unknown at this stage (24/03/2019).  Further, the method of connecting the GUI Front End is also unknown.
 
 We have to "marry" the results of the above with the following (for Android), similar for iOS:
 
    https://medium.com/@anthonymo/elastos-h5-dapp-development-walkthrough-25d734458160  
    
    and also (thus far, 24/03/2019, apparently not fully integrated):  https://github.com/cyber-republic/elastos-smartweb-alpha
    
    The latter 2 references concern the Elastos Trinity Browser System.  Trinity works within the ionic framework:
    https://ionicframework.com/docs/intro .  Ionic can work with the Apache Cordova System, and does so here for Trinity/Ionic.  This means desktop, android and iOS devices are supported.

It seems there is some work to be done by the Elastos people before the targeted date of end 2019 for completion of a production version of Trinity Browser, and a full system of signing and deploying DApps becomes possible, at least at development level.

  A sample of a Trinity DApp is to be found at: https://github.com/elastos/Elastos.Trinity.Alpha.DApp.Demo.CarTest
  
  Note, with the above sample DApp, that there is no apparent connection to a database/blockchain or "backend".  This presents a problem to us, leaving no model to follow.

