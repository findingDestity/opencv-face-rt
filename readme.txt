To build on OS X Mountain Lion

brew install opencv

g++ -L/usr/local/lib -lopencv_legacy -lopencv_objdetect -lopencv_nonfree -lopencv_highgui -lopencv_imgproc -lopencv_core -lopencv_video -I/usr/local//Cellar/opencv/2.4.3/include/opencv/ OnlineFaceRec.cpp