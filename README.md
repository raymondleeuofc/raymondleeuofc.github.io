# ENGO551/651 - Lab 5 Assignment
The objective of the lab was to gain experience with the MQTT protocol and learn hwo to build a simple IoT Geoweb app. 

## Important Folders and Files
- index.html : the IoT Geoweb app file (given functionality via Github pages)

## Requirements Met
1. From the web application, the user is shown which MQTT message broker host and port they are on. 
2. The user can click the Start/End button to establish/finish the connection, additonally they cannot switch their host and/or port until the connection is ended. 
3. In the case where the user is disconnected, they will be automatically reconnected before being notified they were disconnected. 
4. Users can publish messages to any topic available, and from MQTTX we can see the messages that were sent as well as any locations that were shared. 
5. The user can share their location by clicking the "Share my status" button after which, a Geojson message is published to the topic ENGO_551/raymondlee/my_temperature.
6. The map in the web application will show the current location with colours ranging from blue, green, and red which correspond to a range of temperatures. They can also see their current temperature when clicking on the icon. 
7. From MQTTX, users can also publish messages, with Geojson messages updating the location on the browser web application.
8. The web application can also be used from smartphones or other mobile devices capable of geolocation. 

## Additional Details about the Lab Assignment 
To run the IoT Geowebb app please do the following:
1. Set up the connection using test.mosquito.org as the MQTT message broker and 1883 as the port (8081 for the website port)
2. Open the web application via: [raymondleeuofc.github.io](https://raymondleeuofc.github.io/)
3. Enjoy playing around with the messages! :D