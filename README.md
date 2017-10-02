# zoneminder
Zoneminder install script

I have tested this on budgie-remix 16.04-1 desktop x64 and Ubuntu 16.04-1 server x64. This shell script should work on and Ubuntu 16.04 desktop (Mint, Lubuntu et. al.). You do not have to have LAMP, Apache or MySQL installed to run this. The script will install everything Zoneminder needs to function and set up Zoneminder!

WARNING: This script installs Mariadb Server and Client and will replace MySQL if it is installed!!!

Copy the file, zm_install, to your home directory.

Open a terminal and run:

<code>chmod 755 zm_install</code>

Start the script by entering:

<code>./zm_install</code>

Follow the prompts. Things are pretty simple till you get to adding the timezone to PHP then you will need to know how to operate Nano. As a help you can see how it is done in the procedure above.

I did not include the fix for the API in this script but it is an edit to apache2.conf which is shown on above procedure.

WARNING: This script installs Mariadb Server and Client and will replace MySQL if it is installed!!!

Good Luck! 
