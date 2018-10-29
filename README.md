# face-trainer-instagram
A simple proof of concept for a face recognition system that trains itself on an instagram account
This application comprises of 3 parts

### Face Downloader
Crawls the https address of an instagram account and downloads all the faces

### Face Clustering
filters all the faces that aren't related to the main person's instagram account

### Face Dataset
Trains the clustered faces


Tested with https://www.instagram.com/mirandakerr/ @Mirandakerr, you results may vary since new pictures might be uploaded. if you need to use a different account, just change the instagram account url and try it again. Please note that accounts with a larger ratio of selfies would be better


### Libraries used
- selenium (using phantomjs)
- face_recognition
- imutils
- PIL
- numpy
- opencv 3
- sklearn
