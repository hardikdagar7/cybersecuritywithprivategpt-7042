Latest Logs From Latest Build
==============================

Generated On: 2024-11-28 21:59:07 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/hardikdagar7/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-11-28_21:57:23] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-11-28_21:57:24] STEP 2: Create topics started

  [INFO 2024-11-28_21:57:35] STEP 2: Completed

  [INFO 2024-11-28_21:57:40] STEP 3: producing data started

  [INFO 2024-11-28_21:57:42] STEP 4: Preprocessing started

  [INFO 2024-11-28_21:57:43] MQTT connection established...

  [INFO 2024-11-28_21:57:44] STEP 4: Preprocessing started

  [INFO 2024-11-28_21:57:45] STEP 7: Visualization started

  [INFO 2024-11-28_21:57:51] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-11-28_21:57:58] STEP 8: Starting docker push for: hardikdagar0207/cybersecuritywithprivategpt-7042-amd64

  [INFO 2024-11-28_21:57:58] STEP 9: Success starting Qdrant.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant

  [INFO 2024-11-28_21:58:05] STEP 9: Starting privateGPT

  [INFO 2024-11-28_21:58:21] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit fbff3b1e3f36 hardikdagar0207/cybersecuritywithprivategpt-7042-amd64 - message=0

  [INFO 2024-11-28_21:58:26] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --gpus all -v /var/run/docker.sock:/var/run/docker.sock:z --env PORT=8001 --env TSS=1 --env GPU=1 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-with-gpu-nvidia-amd64

  [INFO 2024-11-28_21:59:01] STEP 8: Successfully ran Docker push: docker push hardikdagar0207/cybersecuritywithprivategpt-7042-amd64 - message=0

  [INFO 2024-11-28_21:59:06] STEP 10: Started to build the documentation

  [INFO 2024-11-28_21:59:07] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


