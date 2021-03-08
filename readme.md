Ansible and Jupyterlab   
=====

# Install Ansible   
packages=ansible,libzmq-devel,libffi-devel,python37-devel  

setup-x86_64.exe -q --packages=ansible,libzmq-devel,libffi-devel,python37-devel   

no admin   
setup-x86_64.exe --no-admin -q --packages=ansible,libzmq-devel,libffi-devel,python37-devel   

# Install Jupyterlab   

pip3.7 install jupyterlab   


# Offline Install
   
1. pip3.7 install wheel-0.36.2-py2.py3-none-any.whl   
2. pip3.7 install --no-index --no-build-isolation *   
