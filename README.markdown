### INSATLL

To install MongoDB on your Ubuntu OS, see [http://www.mongodb.org/display/DOCS/Building+for+Linux](http://www.mongodb.org/display/DOCS/Building+for+Linux "")

After installed it, then run the installer script: 

    chmod +x ./installer # make it executable
    sudo ./installer     # run
    
Done! Now you can get it up and running, just run the init script like this:

    sudo /etc/init.d/mongodb start
    
Usage: sudo /etc/init.d/mongodb {start|stop|force-stop|restart|force-reload|status}

### RESOURCES

- [MongoDB docs: Building for Linux](http://www.mongodb.org/display/DOCS/Building+for+Linux "MongoDB docs: Building for Linux")
- [Installing MongoDB on Ubuntu](http://brilliantcorners.org/2010/01/installing-mongodb-on-ubuntu "")
