# HIVE_installation
##prerequsites: 
1.7zip-in order to extract tar.gz
2.Installing Hadoop- you must have a Hadoop Cluster installed and running
3.Apache Derby-Apache Hive requires a relational database to create its Metastore

**step 1: Downloading Apache Hive binaries
**step 2:Open command prompt, go to the folder where you have download Hive and run the following command:

$ tar -xvf apache-hive-3.1.1-bin.tar.gz

**step 3:add Hive path to the environment variable. Open the environment variable window by searching it in the start menu. 
Next, refer to the following pictures to add path:











**step 4:Configuring Hive:Go to the hive folder and open the conf folder in it.
Now copy the file hive-default.xml.template and paste it and rename the new file to hive-site.xml






Open the hive-site.xml file and find the property







Replace <IP address of your host> to your IP address.

Done. Hive is installed. To verify the installation, open the command prompt and run the following:

$ hive –help




