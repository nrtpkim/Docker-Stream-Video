# Docker-Stream-Video
This docker for stream video file to rtsp protocol. The video that stream can receive on same network.

### How to run this docker & Receive stream
1. Insert videos that you want to stream to ./assets/videos

2. Edit file name on row 27 of docker-compose.yaml

3. Run following this command 
`sudo docker compose up -d`

4. if you want to connect rtsp
url = `rtsp://<IP-address>:8554/teststream`
