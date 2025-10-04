
Installation
============

1. Clone the GitHub repository and navigate into the project directory:
---------------------

.. code-block:: bash

   git clone https://github.com/xxdwdwd/SpaMIE.git
   cd SpaMIE
      

2. Create a new conda environment and activate it:
------------
For convenience, we recommend using a separate conda environment for running SpaMIE. Please make ensure annaconda3 is installed on your system. If you haven't installed it yet, you can download and install Anaconda3 from the official Anaconda website (https://www.anaconda.com/products/individual).

.. code-block:: bash

   #Create an environment called SpaMIE

   conda create SpaMIE_env python=3.9

   #Activate your environment

   conda activate SpaMIE_env


3. Install core dependencies and SpaMIE:
------------

.. code-block:: bash

   # dependencies
   pip install -r requirements.txt


   #Install SpaMIE

   pip install -e . or pip install dist/SpaMIE-0.1.0-py3-none-any.whl

 
   