# nuodb-utilities - This repository is a collection of NuoDB utilities. Each contains a README with description and run instructions.

Click Download and run

   $ unzip nuodb-utilities-master.zip

Then, change directory to nuodb-utilities-master directory and copy utilities to your NuoDB server

   $ cd nuodb-utilities-master

untar the utility using

   tar -xvf filename.tar

Then, follow the README instrutions to install or run the utility.

nuodbUpdateUserIndexesV2.tar -
This is a Linux only utility. In NuoDB v3.0 introduced a new index format (Ver2). It provides improved index performance and also automatically updates index statistics periodically. After upgrade to v3.0 run this script to update your user indexes to the new index format and version.

