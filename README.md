# springboot-gifit
creates gir from mp4 file

to upload cat.mp4 from main dir run:
<p>
<b>curl -F file=@cat.mp4 -F start=0 -F end=0 -F speed=1 -F repeat=0 localhost:8080/upload</b>
<br>
to use this app the "mvn install" need to be run on 'springboot-autoconfigure' first.
<p>
springboot-autoconfigure contains autoconfiguration for this project. 