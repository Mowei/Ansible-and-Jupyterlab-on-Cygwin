Ansible and Jupyterlab   
=====

# Install Ansible   
packages=ansible,libzmq-devel,libffi-devel,python37-devel  

setup-x86_64.exe -q --packages=ansible,libzmq-devel,libffi-devel,python37-devel   

no admin   
setup-x86_64.exe --no-admin -q --packages=ansible,libzmq-devel,libffi-devel,python37-devel   

# Install Jupyterlab   

pip3.7 install jupyterlab   

or

cd jupyterlab   
pip3.7 install *   


# Offline Install

1. Download pyzmq-17.0.0.tar.gz replace pyzmq-22.0.3.tar.gz  
2. tar -zxf argon2_cffi-19.1.0.tar.gz ;cd argon2_cffi-19.1.0 ; python3 setup.py install .
3. pip3.7 install *.*
https://pypi.org/project/pyzmq/17.0.0/#files
