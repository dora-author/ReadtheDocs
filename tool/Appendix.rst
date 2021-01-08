***********************************************
Appx. How to Install mobilgene A Studio License
***********************************************

To get mobilgene A Studio License, proceed as follows:

|
| 1. Create your ``.cv2`` file.
|
|  1) Download the license utility file ``mobilgene_A_license_utils.zip``.

.. hint:: ``mobilgene_A_license_utils.zip`` is included in the distributed tools package.
|
|  2) Install the license utility file as follows:

   .. code-block:: bash 

       $ unzip mobilgene_A_license_utils.zip
       $ tar -xvzf aksusbd-7.100.1.tar.gz
       $ cd aksusbd-7.100.1
       $ sudo ./dinst
   ..
|
|  3) You can check the installed licenses as follows:
|    3-1) Access http://localhost:1947 by Browser on Linux OS.
|    3-2) If you see the screen below, the license has been successfully installed.
     
     .. image:: ../_static/tool/images/appx_1.png
|     
|  4) Create ``.c2v`` file as follows.

   .. code-block:: bash  

       $ cd ../usr-lib-copy
       $ sudo cp ./* /usr/lib
       $ cd ..
       $ sudo chmod +x hasp_update
       $ ./hasp_update f {your name}_{company name}.c2v  
   ..

|
| 2. Send the created ``.c2v`` file to Autron tool manager.
| Autron tool manager will check your file and provides you with the ``.v2c`` license file.

.. hint:: The received ``.v2c`` file name is in the form of {your Key ID}.

|
| 3. Install the license file in your Linux PC.
|
|  1) Move the ``.v2c`` file to the path where the ``hasp_update`` file executed in Step 1-4) is located.
|  2) Run the ``.v2c`` file as follows:

   .. code-block:: bash

       $ ./hasp_update u {your Key ID}.v2c
   ..

.. warning:: | Run the command in Step 3-2) above only once. Otherwise, the following error message appears.
             | ``hasp_update failed with status 65``

|
| 4. Now, you have successfully installed mobilgene A Studio license.
|    Next, you can run mobilgene A Studio on your Linux OS.

.. hint:: For more information about running mobilgene A Studio, See the User Guide of mobilgene A Studio.




 






