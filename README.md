This is a project that allows for an external client to remotely control the tv webpage. It stores 4 key variables, channel, power, volume, and starting_video. These variables control the state of the application. The power depicts whether the tv is on or off, the channel determines which video is playing, the volume, although doesn't work with iFrame, would control the loudness of the video, and the starting_video is what points to the video source. 

These variables are updated either by the client on the website, or remotely. It's a simple collection of data. 

# Depencencies
* pip3 install Flask
* pip3 install flask-socketio
* pip install gevent gevent-websocket

## Dependency configurations
* Flask-SocketIO==4.3.1

