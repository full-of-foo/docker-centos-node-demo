==Demo CentOS Node App

Just fiddling with Docker (simple Node app)

===Getting Started (OS X)

 - Install VirtualBox https://www.virtualbox.org/wiki/Downloads
 - Install Docker deps `brew install boot2docker docker`
 - Initialise and start your tinyVM `boot2docker init && boot2docker up`
 - Run le services `docker run -p 8080:8080 -t app`
 - Open le browser `open http://$(boot2docker ip):8080`
