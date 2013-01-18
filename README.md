sandstone-wikimo
================

install
=======
    git clone git@github.com:Hoosteeno/sandstone-wikimo.git

    cd sandstone-wikimo

    virtualenv venv

    source venv/bin/activate
    
    python bootstrap.py 

    bin/buildout 

run (in dev)
============

    bin/paster serve --reload proxy.ini
