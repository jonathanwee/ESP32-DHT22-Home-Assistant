# ESP32-DHT22-Home-Assistant

IoT monitoring of temperature and humidity

Add the ESPHome add-ons repository to your Home Assistant instance. You can do this by navigating to the "Add-on store" tab in the Supervisor panel and then entering https://github.com/esphome/hassio in the "Add repository" field after selecting "Repositories" from the top-right menu.
Now scroll down and select the "ESPHome" add-on.
Press install to download the add-on and unpack it on your machine. This can take some time.
Optional: If you're using SSL/TLS certificates and want to encrypt your communication to this add-on, please enter true into the ssl field and set the fullchain and certfile options accordingly.
Start the add-on, check the logs of the add-on to see if everything went well.
Click "OPEN WEB UI" to open the ESPHome dashboard. You will be asked for your Home Assistant credentials - ESPHome uses Home Assistant's authentication system to log you in.
