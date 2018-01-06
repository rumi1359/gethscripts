# gethscripts
Some starter scripts to help setup a private geth node in 8 easy steps:

1. Download all the files in this repository to somewhere on your harddrive.
2. Make a directory to hold your project: `~$ mkdir myProject`
3. Copy `gethmake.sh` into this project directory and give it execution rights: `/myProject$ chmod a+x ./gethmake.sh`
4. Run: `/myProject$ ./gethmake.sh` 
5. This should make two folder inside your project directory: *main* and *truffle*
6. Go inside the *main* folder and run: `~/myProject/main$ ./gethinit.sh`
7. Still inside the *main* folder run: `~/myProject/main$ ./gethstart.sh`
8. A private Ethereum geth node should be running in the terminal. You're done!
