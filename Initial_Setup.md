#Loading Firmware

*First open the ground station (QGControl) and select the gear button to initialize setup

*Connect the Pixhawk to your OC via USB

*Select your firmware (PX4) and click OK

*The firmware will automatically setup/upgrade

###Wait till inistallation is complete and select your airframe (Std Airplane)

    click apply and restart to indicate your airframe data

###You can now connect via the telemetry

#Hardware Assembly

###Pixhawk Wiring

    Check the PX4 user guide:  https://docs.px4.io/master/en/assembly/quick_start_pixhawk.html

###Power Module Schematic (GM v1.0)

    ![powermodule-analog-pixhawk.png]

###Airspeed Sensor Schematic (Pixhawk Airspeed Sensor GM3 v1.1)

    Check this pdf: https://3dr.com/wp-content/uploads/2017/03/Pixhawk-Digital-Airspeed-Sensor-Manual-V1-2.pdf

###I2C Pinout

     ![RangeFinder_MaxBotixI2C_Pixhawk.jpg]

**Note: It's necessary to connect all the ports correctly and check the pinout schematics due to mitigate any possible risks.
