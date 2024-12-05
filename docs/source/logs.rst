Latest Logs From Latest Build
==============================

Generated On: 2024-12-05 20:49:26 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/Project122024/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-12-05_20:44:31] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-12-05_20:44:37] STEP 2: Create topics started

  [INFO 2024-12-05_20:45:01] STEP 2: Completed

  [INFO 2024-12-05_20:45:19] STEP 3: producing data started

  [INFO 2024-12-05_20:45:25] MQTT connection established...

  [INFO 2024-12-05_20:45:26] STEP 4: Preprocessing started

  [INFO 2024-12-05_20:45:31] STEP 4: Preprocessing started

  [INFO 2024-12-05_20:45:34] STEP 7: Visualization started

  [INFO 2024-12-05_20:45:41] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 52087

  [INFO 2024-12-05_20:46:00] STEP 9: Starting privateGPT

  [INFO 2024-12-05_20:46:11] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-12-05_20:46:15] STEP 8: Starting docker push for: tmltss/finalproject-93bc-amd64

  [INFO 2024-12-05_20:46:48] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit 58d53137bba0 tmltss/finalproject-93bc-amd64 - message=0

  [INFO 2024-12-05_20:48:15] STEP 8: Successfully ran Docker push: docker push tmltss/finalproject-93bc-amd64 - message=0

  [INFO 2024-12-05_20:49:23] STEP 10: Started to build the documentation

  [INFO 2024-12-05_20:49:28] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


