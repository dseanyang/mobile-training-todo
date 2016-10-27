## Requirements

- Vagrant 1.8.1
- VirtualBox 5.0.6

## Getting Started

1. Install VirtualBox from the installer on the USB.
1. Install Vagrant from the installer on the USB.
1. Copy **couchbase-mobile-training.box** and **Vagrantfile** to a directory on your machine.
1. Open a new Terminal/Command Prompt and import the box image.

    **Mac / Linux**
    ```bash
    cd ~/Desktop/vagrant
    vagrant box add couchbase-mobile-training couchbase-mobile-training.box
    ```
    
    **Windows**
    ```bash
    cd c:\Users\Username\Desktop\vagrant
    vagrant box add couchbase-mobile-training couchbase-mobile-training.box
    ```
   
1. Start the VMs.

    ```bash
    vagrant up
    ```
    
    |VM Name|Host Name|IP|
    |:------|:--------|:--|
    |VM1|couchbase-server|192.168.34.11|
    |VM2|sync-gateway1|192.168.34.12|
    |VM3|sync-gateway2|192.168.34.13|
    |VM4|nginx|192.168.34.14|
    |VM5|sync-gateway3|192.168.34.15|

1. Start the Deploy lesson of the Training.

### Links to resources

- http://cbmobile-bucket.s3.amazonaws.com/connect-2016-training/putty-0.67-installer.msi
- http://cbmobile-bucket.s3.amazonaws.com/connect-2016-training/vagrant_1.8.1.dmg
- http://cbmobile-bucket.s3.amazonaws.com/connect-2016-training/vagrant_1.8.1.msi
- http://cbmobile-bucket.s3.amazonaws.com/connect-2016-training/Vagrantfile
- http://cbmobile-bucket.s3.amazonaws.com/connect-2016-training/VirtualBox-5.0.26-108824-OSX.dmg
- http://cbmobile-bucket.s3.amazonaws.com/connect-2016-training/VirtualBox-5.0.26-108824-Win.exe
- http://cbmobile-bucket.s3.amazonaws.com/connect-2016-training/couchbase-mobile-training.box