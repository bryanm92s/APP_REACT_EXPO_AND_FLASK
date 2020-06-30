# APP_REACT_EXPO_AND_FLASK


This is the front of a mobile and web application to view properties.

# Back-end

The backend of this application is created with Node JS and Mongo DB Atlas as a database.
to run the backend clone this repository and run: npm i in the APP_REACT_EXPO_AND_FLASK\REACT\propriertyapp\server

# Interface

To run the application front-end, clone this repository and run: npm i in the APP_REACT_EXPO_AND_FLASK\REACT\propriertyapp directory
You must ensure that you have globally installed expo and expo-cli packages on your machine before the propriertyapp application can run.

# App

Once you have everything installed and the backend running, just run expo start at the root of this project (APP_REACT_EXPO_AND_FLASK\REACT\propriertyapp) and the expo will launch. You choose to run it in the browser, device emulator or real device through the QR code, but remember that alerts are not compatible with the web browser.

# Interface Web

To run the application front-end, clone this repository and run: python app.py in the APP_REACT_EXPO_AND_FLASK\FLASK\ directory and you should enter the link http://127.0.0.1:8081/

# Videos

Here you can find two videos with the explanation of the application flow. (REACT, FLASK)
APP_REACT_EXPO_AND_FLASK\VIDEOS\

# User created for the mobile application and the web application:

email: cesdefinal@cesde.com

password: 123456

NOTE: In the mobile application (APP_REACT_EXPO_AND_FLASK\REACT\propriertyapp) you can create accounts by entering email and password (Validations were made)

# Changes to make the mobile app and web app work.

1. In the APP_REACT_EXPO_AND_FLASK\REACT\propriertyapp\screens\ folder of React (propriertyapp) you must change the IP address: 192.168.1.13 (endpoints) for the IP address of your machine.

2. In the web application developed in Python (Flask) there is a APP_REACT_EXPO_AND_FLASK\FLASK\models\ directory and within it there is a file called requests_api.py there you must change the url of the RequestsApi class for the address of your machine.

3. In the creation of the properties in React (propriertyapp) the images can be loaded from the gallery or take a photo from the device.

4. In the creation of the properties in Flask the images are added randomly.





# Credits

Alejandra Bolivar Durango

Daniel Cadavid Zuleta

Wilfer Andrés David Ocampo

Bryan Guerrero Morales
