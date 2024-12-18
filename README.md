# BlueIris
docs
CloudEdge Camera DoorRing Bell

How to add CloudEdge camera/doorbell to BlueItis?

J5 is a 2K/3MP resolution smart doorbell (CloudEdge version) can support ONVIF connection, the camera can deliver continuous video stream via RTSP protocol to other ONVIF compliant devices. Hence users can integrate this doorbell into other video system. The J5 smart doorbell can work with Blue Iris, Dahua/Hikvision NVRs, Synology and Qnap NAS, iSpy/Agent DVR. [OG Link]([url](https://shop.tuyaoem.com/cloudedge-cameras-doorbells-ispy-agent-DVR?srsltid=AfmBOop6KJWvudVpwUibeIY_9g1kTIJVvtAMGo_8p7ATL5G-qUp8a_BZ)) 

The next, using the CloudEdge app and tapping “Onvif setting” then enable “Onvif” and set a new password for the connection.

Username: admin (should not be changed)

Password: ****** (your onvif password set via CloudEdge app)

Service URL: http://192.168.0.179:8000/onvif/device_service

RTSP port Overrite: 0

Timeout: 15

2304x1296: rtsp://admin:onvif150@192.168.0.179:8554/Streaming/Channels/101; 640x480: rtsp://admin:onvif150@192.168.0.179:8554/Streaming/Channels/102.



For BlueIRIS is different

RTSP port: 8854

ONVIF port: 8000

[MainStream]: /Streaming/Channels/101



![image](https://github.com/user-attachments/assets/f936af0f-a60e-4a95-8eac-5d3b997a221a)


# AMICCOM Camera (JAWA app)
Smart IP Camera C_22002 | ID: 0008KCD0JTAL9CKA


RTSP port: 2600

ONVIF port: 8999

[default]: /

![image](https://github.com/user-attachments/assets/21f88834-d29b-4ddb-8c03-9099cc332bd5)
