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
