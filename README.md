#C[loud]S[cripts]

CloudScripts (CS) is where all my day to day scripts, templates and frameworks are stored.

##Installation
Execute only this command to install all the scripts and files of CS in their respective location.

```
curl -s http://cs.johandry.com/install | bash
```

##Updates
Once the scripts are installed, they can be updated with the parameter ``--update``. Example: ``sm --update``

If you only want to update the Common Utility script, execute:

```
bash ~/bin/common.sh --update
```
##Maintenance
To setup the project for the first time, execute this to clone all the required branches and create the right structure

```
curl -s http://cs.johandry.com/setup | bash
```

To push a modification deploy the changes with the ``deploy`` script.

```
./deploy -m 'Description of the change'
```

##TODO, Ideas & Work in progress

* Create a ~/.servers directory *.servers files. If there is no *.servers file in current directory, search there.
* Make servers files instead of entries in a file. Useful to auto-complete and store notes and data inside a server file.