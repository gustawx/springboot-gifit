# springboot-gifit
creates gir from mp4 file

To upload file use home page or run curl command, for e.g. to upload cat.mp4 from main dir run:
<p>
<b>curl -F file=@cat.mp4 -F start=0 -F end=0 -F speed=1 -F repeat=0 localhost:8080/upload</b>
<br>
to use this app the "mvn install" need to be run on 'springboot-autoconfigure' first.
<p>
springboot-autoconfigure contains autoconfiguration for this project.
<p>
To build docker image first compile code and then run:<br>
mvn docker:build 