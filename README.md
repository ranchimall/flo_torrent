# FLO Torrent
FLO Torrent is a decentralized platform for torrent storage with verification of the uploader  

### Live URL for FLO Torrent:
*https://ranchimall.github.io/flotorrent/*  

## Mission statement
Torrent technology is widely used by millions of people to share files without the need for a centralized server. 
But yet, the torrent file itself is required to be stored in a website (server) for the users to spread the torrent.
Thus it's not completely decentralized and any torrent can be removed by the torrent website provider.
Once a torrent is been removed from the torrent search websites, no client users can download that torrent any longer.
Hence it is required to store the torrent file in a decentralized medium so that no one can remove the torrent's existence.

This project allows the torrent uploader to permanently store the torrent file in the decentralized blockchain.
Any torrent user can download torrent files from the blockchain without the use of a centralized server.

Since the Torrent file is stored in the blockchain, no one can remove it from the blockchain. 
Thus any torrent file uploaded by users will be stored permanently and can be accessed by other users at any time.

Another issue is to prevent fake uploaders to use the name of the reputed uploaders to upload the torrent pretending to be them. 
In the FLO Torrent Project, the FLO_ID is used to upload the torrent to the blockchain. 
Hence the transaction is verified for the signature of the valid FLO_ID user and no fake uploaders can use the FLO_ID of reputed torrent uploaders
Thus the uploader ID is verified as well as the identity of the uploader is anonymous.  

## Download torrent files  
1. Access the home page of the FLO Torrent app https://ranchimall.github.io/flotorrent/
2. Search for the file (movies, music, documentary, games, etc)
3. The user can also select the files listed in the home page
4. Click on the "Get Torrent" button
5. This will download the torrent file for the selected item
6. Use a torrent client such as BitTorrent or µTorrent to open the downloaded torrent file
7. For each torrent file, the indexed entry on the blockchain can be checked by clicking "see the index entry on blockchain" under the torrent file


## FLO Torrent Uploader
FLO_torrentUploader is used to upload the torrent file to the blockchain.  

### Requirements to Upload
1. A valid FLO ID (Public Address and Private Key Pair) 
2. Minimal fee to upload the torrent (Scales with the file of the torrent file)
3. 
### Instructions to Upload
1. Open the `FLO_torrentUploader.html` in a Web Browser
2. Enter Uploader's FLO_ID (FLO address)
3. Browse/Select the torrent file from the local storage.
4. Enter the Torrent name, type, description, and tags in the respective fields
5. Click the `Upload torrent` button
6. The balance of the FLO_ID and the fee required to upload will be displayed in the alert box.
7. Confirm and Enter the Private key of the FLO_ID when prompted.
8. The torrent file will be uploaded to the blockchain and the reference txid will be displayed.

## Android
Android users can directly download the FLO_Torrent.apk and Install the app.
To download the apk: Click [View raw](https://github.com/ranchimall/FLO_Torrent/blob/master/FLO_Torrent.apk?raw=true)
