# Record
LabVIEW code to operate Optris thermal cameras.

The software development kit (SDK) must be installed for the code to function.

Implementation of camera preview footage in LabVIEW is in progress.

To use:
<<<<<<< Updated upstream
1. Open `thermalCamera.vi`.
2. Run the VI.
3. Wait for the terminal to indicate that both video and socket servers are listening.
4. Click **Connect Client** to connect server.
5. Wait for terminal to indicate that camera calibration has been complete and temperatures are reliable. 
6. Press Record
=======
1. Open `thermalCamera.vi`
2. Set the server path to `imagerServer.py`.
3. Run the VI.
4. Wait for the terminal to indicate that the thermal data is ready.
5. Click **Connect Client** to enable the recording features.
>>>>>>> Stashed changes

> **Note:** Before recording, press `flag` for best temperature accuracy. 


