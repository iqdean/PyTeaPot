# PyTeaPot

## Description
Quaternion Euler Cube Rotation Visualizer

This repo was based off of [thecountoftuscany's PyTeapot-Quaternion-Euler-cube-rotation](https://github.com/thecountoftuscany/PyTeapot-Quaternion-Euler-cube-rotation)

## Change List
- modified to add socket-based client/server interface to bne055 sendQuaternion node which subscribes to /bne055/imu and broadcasts over udp ip:port socket to PyTeapot 
