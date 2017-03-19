# aframe-movement
This shows how to move around in the aframe vr world based on the orientation of the user. Which ever direction the user looks, the camera moves in that direction. Look down to stop movement. Look up to start movement.

# Installation Steps:
For Desktop:
1. Download the folder
2. The file has to be hosted on a server to avoid CORS issues. You can optionally run the test.py which hosts the app in cherrpy
3. Once the app is hosted, run the aframe_camera_movement_demo.html file

For Mobile:
1. Download the folder
2. The file has to be hosted. You can use download a simple HTTP server from the playstore or appstore.
3. Once the app is hosted, run the aframe_camera_movement_demo.html file. You would need a VR viewer like Google Cardboard.

# What does this app do?
This app is VR app in which different color cubes are placed in four directions. When you see the sky at an angle of more 15 degrees, you will start to move in the VR space. Now depending on the direction you look, you will start to move. If you want to stop moving, just look at the ground at an angle of greater than -15 degrees.
