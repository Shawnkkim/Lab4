# Lab4

This project is building a simple web application that uses the javascript geolocation API and a simple web mapping application to visualize the current location. GeoJSON is implemented in order to acquire the user's location and the tempearture at that location. After that these values are sent to the topic. MQTT protocol was also implemented in the web application.

Information that needed to establish a connection to the server are as follows:
 [Server: test.mosquitto.org]
 [Port: 8081]
 [Subscribe to the topic (course_name/your_name/my_temperature)]
