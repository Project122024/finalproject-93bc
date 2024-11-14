Latest Logs From Latest Build
==============================

Generated On: 2024-11-14 19:59:10 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/Project122024/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-11-14_19:50:37] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-11-14_19:50:55] STEP 2: Create topics started

  [INFO 2024-11-14_19:51:54] STEP 2: Completed

  [INFO 2024-11-14_19:52:24] STEP 3: producing data started

  [INFO 2024-11-14_19:52:36] MQTT connection established...

  [INFO 2024-11-14_19:52:38] STEP 4: Preprocessing started

  [INFO 2024-11-14_19:52:47] STEP 4: Preprocessing started

  [INFO 2024-11-14_19:52:52] STEP 7: Visualization started

  [INFO 2024-11-14_19:52:59] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 54689

  [INFO 2024-11-14_19:53:19] STEP 9: Starting privateGPT

  [INFO 2024-11-14_19:53:46] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-11-14_19:54:05] STEP 8: Starting docker push for: tmltss/finalproject-93bc-amd64

  [INFO 2024-11-14_19:55:16] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit dda7d2585a33 tmltss/finalproject-93bc-amd64 - message=0

  [INFO 2024-11-14_19:58:33] STEP 8: Successfully ran Docker push: docker push tmltss/finalproject-93bc-amd64 - message=0

  [INFO 2024-11-14_19:59:07] STEP 10: Started to build the documentation

  [INFO 2024-11-14_19:59:15] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


