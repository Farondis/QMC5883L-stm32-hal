Written by Sercan DEMIRHAN.



Written for general use.

-I2C communication port setting is in .h file. (QMC5883L_I2C_PORT, default & hi2c1)
- In its simplest form,

  int16_t is X, Y, Z;
    qmc5883l_ınitializ(MODE_CONTROL_CONTINUOUS, OUTPUT_DATA_RATE_200HZ, FULL_SCALE_2G, OVER_SAMPLE_RATIO_512);
    qmc5883l_read_dat(&X, &Y, &Z);












QMC5883L-stm32-hal
