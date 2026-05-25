Installation
============

1. Clone the GitHub repository and navigate into the project directory:
-----------------------------------------------------------------------

.. code-block:: bash

   git clone https://github.com/xxdwdwd/SpaMIE.git
   cd SpaMIE


2. Create a new conda environment and activate it:
--------------------------------------------------
For convenience, we recommend using a separate conda environment for running SpaMIE. Please ensure Anaconda3 is installed on your system. If you haven't installed it yet, you can download and install Anaconda3 from the official Anaconda website (https://www.anaconda.com/products/individual).

.. code-block:: bash

   # Create an environment called SpaMIE_env
   conda create -n SpaMIE_env python=3.9

   # Activate your environment
   conda activate SpaMIE_env


3. Install core dependencies and SpaMIE:
----------------------------------------

.. code-block:: bash

   # Install dependencies
   pip install -r requirements.txt

   # Install SpaMIE
   pip install -e . 
   # or 
   # pip install dist/SpaMIE-0.1.0-py3-none-any.whl


4. Download demo datasets:
--------------------------
We provide the following datasets via Baidu Netdisk for testing and reproducing our results:

* **Simulated Data (simu)**
  * Link: https://pan.baidu.com/s/1kxq0a2ZlDCRi3McPV1hSxg?pwd=n1bk
  * Extraction Code: ``n1bk``

* **Mouse Spleen Data**
  * Link: https://pan.baidu.com/s/1kictyMK0pmqII0MqRkZ7-Q?pwd=r9ea
  * Extraction Code: ``r9ea``
