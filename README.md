Written by Sercan DEMIRHAN.



Written for general use.

-I2C communication port setting is in .h file. (QMC5883L_I2C_PORT, default & hi2c1)
- In its simplest form,


  
  int16_t X, Y, Z;
  
    QMC5883L_Initialize(MODE_CONTROL_CONTINUOUS, OUTPUT_DATA_RATE_200HZ, FULL_SCALE_2G, OVER_SAMPLE_RATIO_512);
    
    QMC5883L_Read_Data(&X, &Y, &Z);










QMC5883L-stm32-hal
