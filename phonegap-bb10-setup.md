Download the Blackberry Momentics IDE and use it to install the Blackberry NDK. (version 10.2 as of this writing)
After installing the NDK, source ~/bbndk/bbndk-env.sh in your .bashrc file

Install node, then "sudo npm install -g cordova"

Install chrome along with the Ripple extension. Ripple will not work on local files; set up a simple web server.
You can use Ripple to preview the application ('project/www/index.html').

Create your app: 
    cordova create myapp
    cd myapp
    cordova platform add blackberry10

Consult the BB10 platform guide found on the cordova documentation on how to prepare for signing.
Be sure to have your BB10 device configured to be detected properly by linux:
    Z10 device: Settings -> Storage and Access -> USB Connection -> Connection to Mac 

Deployment information was also included on that page as of this writing.
