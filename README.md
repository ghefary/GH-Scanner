# GH-Scanner
GH-Scanner is a bin built in python to upload sample file | hash to be scanned via Virus total then return the Result on Both Std-Out &amp; CSV file

## Contents  
* [Functions](#Functions) 
* [Requirements](#Req)  
* [How to Use](#Usage)  
* [Demo](#Demo)  
  
## Functions  
1) submit a sample file | hash of  (malware | virus...etc) to be scanned via Virus Total   
2) Result is presented on Std-Out , also saved as a CSV File
  
## Req  
1) Virus Total API Key (free)  ==> Copy Api Key & set it in my_conf.conf like below ex:
                                      [VirusTotal]
                                      PublicAPI: "Paste your API Key here"
  
## Usage  
GH_Scanner.exe [-h] [-file FILE] [-hash HASH] ConfigurationFile

1) positional arguments:
  ConfigurationFile  Configuration file
  
2) optional arguments:
  -h, --help         show this help message and exit
  -file FILE         Path to any file, eg: evil.exe
  -hash HASH         hash to file

## Demo 
Tested with Eicar sample
1) File Submit 


![](https://media.giphy.com/media/p5oGiaN01znIdmGUeV/giphy.gif)

