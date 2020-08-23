# rpi-network-scanner
Raspberry Pi based Nmap scanner setup with Web UI and AWS S3 integration:

This was a fun project where the premise is that a small company with a low budget orders the RPi from a cyber security company, attaches it to their network and runs a scan using the simple web UI. After this, the results are uploaded automatically to an S3 bucket where the (remote) cyber security company can interpret the results and give advice based on them. By being able to do the testing remotely, the client company saves a lot of money because they don't have to pay the cyber company to fly out their employees to do local testing.
