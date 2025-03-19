# social_sleaping_acquisition
Bonsai workflow to power acquisition of social behaviour setup
Bonsai workflows for camera, lickport and thermistor acquisition as well as stepper motor commands using harp devices. 

  **Camera**
  - Basler acA1920-150um with Fujinon C125-0418-5M 4mm
  - GPIO plugged into Harp Behaviour board
    
  **Harp Behaviour Board**
  - Firmware 3.1
  - Harware version 2.0
  - 2 Lickports connected
  - thermistor in analog input
  - GPIO of Camera in DIO
    
  **Harp Timestamp Generator**
  - Clock out to Behaviour, stepper driver and output expander

  **Harp Stepper Driver**
  - connected Sanyo Denki 103H7 series stepper motor
  - 1A current
  - 1NM holding torque
  - 24Volt
  
  **Harp Output Expander**
  - to send randomly distributed ttl signature to Doric Console

Behaviour events are logged using the AEON.acquisition logger 
