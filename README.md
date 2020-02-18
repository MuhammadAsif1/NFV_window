# NFV_window

Execute Test Cases
- Setup env 
   Install virtualenv using pip on director
     $ pip install virtualenv
   Create a virtual environment
     $ virtualenv .env
   Active your virtual environment
     $ source <env-name>/bin/activate
   Install paramiko and sdk package
     $ pip install openstacksdk==0.22.0
     $ pip install paramiko==2.4.2

- Execute Test 
   clone this repository
     $ git clone https://github.com/MuhammadAsif1/NFV_window.git
   Configure NUMA test Case and variables
     $ cd NFV_window/nfv_auto/numa_tests.py
   Run python script
     $ python feature_tests.py
