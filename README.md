# Darkwing Duck

A Rubber Ducky Payload Toolkit


# Using Darkwing Duck

#### Configuring Payloads

darkwing will prompt the user for input for each required parameter within a payload.


#### Deploying Payloads

darkwing can deploy the payload for you. If you choose to deploy the inject.bin manually you will find the file in the injections/ directory.


# Compiling Payloads Manually

cp payloads/<payload.txt> tmp/

vim tmp/<payload.txt>

Make edits as required to the Python formatters ({0},{1}, etc)

java -jar ~/Downloads/java_ducky_encoder/duckencoder.jar -i <payload.txt> -o <inject.bin>


# Accessing MicroSD via Kali VM

Virtual Box -> Machine -> Setting -> USB

Then, add the following USB devices or select the MXTronics MXT USB Device and ATMEL AT32UC3B DFU and click okay.

