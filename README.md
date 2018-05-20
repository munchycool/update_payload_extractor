# update_payload_extractor

sudo add-apt-repository ppa:jonathonf/python-3.6


sudo apt-get update


sudo apt-get install python3.6


pip install backports.weakref

protobuf3 

**Make sure you grab the latest version**
curl -OL https://github.com/google/protobuf/releases/download/v3.2.0/protoc-3.2.0-linux-x86_64.zip

**Unzip**
unzip protoc-3.2.0-linux-x86_64.zip -d protoc3

**Move protoc to /usr/local/bin/**
sudo mv protoc3/bin/* /usr/local/bin/

**Move protoc3/include to /usr/local/include/**
sudo mv protoc3/include/* /usr/local/include/


pip install google-cloud


pip install google


sudo apt-get install python-lzma

**Usage**

./extract.py payload.bin

extracted files will be in output
