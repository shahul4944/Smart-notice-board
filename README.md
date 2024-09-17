# Smart-notice-board
Smart Notice Board Using ESP8266 and LCD (Without I2C)
This project implements a Smart Notice Board using an ESP8266 WiFi module and an LCD display. The notice board allows users to update messages remotely via a web browser by connecting to the ESP8266’s local web server. This eliminates the need for physical intervention to change the displayed information, making it ideal for environments such as schools, offices, and public spaces.

Key Features:

	•	ESP8266 Web Server: The ESP8266 hosts a web interface accessible via an IP address. Users can submit new messages through a simple HTML form.
	•	LCD Display: The new message is displayed on a 16x2 or 20x4 LCD connected directly to the ESP8266 without using an I2C interface.
	•	WiFi Connectivity: The ESP8266 connects to a local WiFi network, enabling any device on the same network to update the notice board.

Working Principle:

	1.	The ESP8266 creates a web server that users can access via their browser.
	2.	The web page features an input form where users can type new messages.
	3.	Upon submission, the ESP8266 reads the message and updates
