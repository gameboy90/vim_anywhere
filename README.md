# Work with vim anywhere. #

## install ##

### linux ###

Execute the `setup.sh`

    sh setup.sh
    OR bash setup.sh (if you are not sure you are using bash for shell default script)

### windows ###

You may need to install GVIM in your system first.

After install, copy all the files in the directory `files` to the `$HOME` directory.

If you dont know what is the `$HOME` directory, open GVIM, type the command below:

    :ehco $HOME

It will output something like:

    C:\Users\srain\     // This is the $HOME

####TODO

In mac, should replace the [`Exuberant CTags`](http://www.scholarslab.org/research-and-development/code-spelunking-with-ctags-and-vim/)

    sudo port install ctags
    sudo ln -sf /opt/local/bin/ctags /usr/bin/ctags 

In Minimum Installation CentOS

    sudo yum install -y ctags
