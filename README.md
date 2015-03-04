# videoTransferOverTCP
simple OpenCV video capture and show with HTTP Streaming

# Reference: http://nashruddin.com/StrEAMinG_oPENcv_vIdEos_ovER_tHe_nEtWoRk

# Compile: 
gcc stream_server.c -o stream_server -I"C:\OpenCV2.1\include\opencv" -L"C:\OpenCV2.1\lib" -lcxcore210 -lcv210 -lhighgui210 -lpthread

# Execute:
	* server: 
	* client: ./stream_client 192.168.0.1 8888 320 240
