/**
  ******************************************************************************
  * @file    ADC/ADC_temperature_Vref_Vbat/readme.txt
  * @author  MCU SD 
  * @version V2.0.0
  * @date    15-Jan-2016 
  * @brief   Description of the ADC/ADC_temperature_Vref_Vbat demo.
  ******************************************************************************
  */

  @brief
    This demo is based on the GD32150R-EVAL/GD32190R-EVAL board, it shows how to 
  use the ADC to convert analog signal to digital data.The ADC is configured 
  in dependent mode, inner channel16(temperature sensor channel),channel17(VREF channel) 
  and channel18(VBAT/2 channel) are chosen as analog input pin. The ADC clock 
  is configured to 12MHz.
    As the AD convertion begins by software,the converted data in the ADC_IDTRx register
  ,where the x is 1 to 3.    
 
  @note
    The analog input pin should configured to AN mode and the ADC clock should 
  below 14MHz for GD32150R(28MHz for GD32190R-EVAL).

/****************** (C) COPYRIGHT 2016 GIGADEVICE *********END OF FILE*********/
