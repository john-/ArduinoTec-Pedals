This implementation uses an [AS5600](https://ams.com/en/AS5600) adaptor [board](https://ams.com/as5600adapterboard) to replace the Hall Effect sensors on the Fanatec CSPV1.

The AS5600 supports analog, PWM and I2C outputs.  ArduinoTec-Pedals supports the analog interface.

The AS5600 provides 12bit resolution over either the entirety of its 360 degree range or can be programmed to provide the full resolution over a smaller angle of rotation.  See the [datasheet](https://ams.com/documents/20143/36005/AS5600_DS000365_5-00.pdf) for programming and other details.

A 3D printed bracket is used to mount the adaptor board to the Club Sport pedal:

- FreeCad file
- STL file

Here is a picture of the board in operation.