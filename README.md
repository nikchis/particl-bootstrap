# particl-bootstrap

This repository contains the bootstrap chain files for the Particl blockchain. Using these files helps shorten the amount of time it takes to sync the wallet since you don't need to sync the blockchain from scratch.

---

## Instructions
If you have never ran the Particl wallet, follow the first set of directions below. If you have already ran the Particl wallet before, follow the second set of directions below.

#### If you have *already* ran the Particl wallet:

1. Download the latest bootstrap files.
1. Find the downloaded *particl-bootstrap.zip* file and double-click. This will unzip the file and show a folder named *particl-bootstrap*.
1. Close and quit the Particl wallet if it is running.
1. Navigate to your OS's respective data directory.

	1. For Windows: `C:\Users\[YourUsername]\AppData\Roaming\Particl\`
		1. Or paste `%appdata%\Roaming\Particl\` into the file explorer path field
	1. For MacOS: `~/Library/Application Support/Particl/`
		1. Open Finder and in the program menu select *Go* > *To Folder* and enter the above path.
	1. For Linux: `~/.particl/`
1. Remove all files and folders **EXCEPT** for *wallet.dat*. **DO NOT** delete the *wallet.dat* file as it contains the private keys for your funds. Deleting this file will result in loss of funds.
1. Inside the downloaded *particl-bootstrap* folder there are `blocks/` and `chainstate/` folders. Move these 2 folders into the Particl wallet's data directory that you just removed files from.
1. If you do not have the latest Particl wallet, download and install it.
1. Run the wallet and syncing should begin at the bootstrap's last block.

#### If you have *never* ran the Particl wallet:

1. Download the latest bootstrap files.
1. Find the downloaded *particl-bootstrap.zip* file and double-click. This will unzip the file and show a folder named *particl-bootstrap*.
1. Move the *particl-bootstrap* folder to your OS's respective data directory.

	1. For Windows: `C:\Users\[YourUsername]\AppData\Roaming\`
		1. Or paste `%appdata%\Roaming\` into the file explorer path field
    1. **Note**: For Windows you must rename the *particl-bootstrap* folder to `Particl`
	1. For MacOS: `~/Library/Application Support/`
		1. Open Finder and in the program menu select *Go* > *To Folder* and enter the above path.
    1. **Note**: For MacOS you must rename the *particl-bootstrap* folder to `Particl`
	1. For Linux: `~/`
		1. **Note**: For Linux you must rename the *particl-bootstrap* folder to `.particl`
1. Download the latest Particl wallet.
1. Install and run the wallet. Syncing should begin at the bootstrap's last block.
