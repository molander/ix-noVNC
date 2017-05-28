# ix-noVNC Thin Client:
    Allows quick stand-up of http VNC from tcp/vncserver for viewing from VR browser


# Make a directory 
    cd in, and run the command to create the VNC fwd
mkdir ix-webVNC

cd ix-webVNC

pkg install py27-websockify

unzip noVNC-thin.zip

websockify 8787 localhost:5900 --web noVNC-thin

# CLIENT:
http://IP_ADDR:8787/vnc.html


