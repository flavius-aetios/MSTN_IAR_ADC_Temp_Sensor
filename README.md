# MSTN_IAR_ADC_Temp_Sensor

This example describes how to use the ADC1 and DMA to transfer continuously converted data from ADC1 to memory. 
The ADC1 is configured to converts continuously ADC channel31 - Temperature Sensor. 
Each time an end of conversion occurs the DMA transfers, in ping-pong mode, the converted data from ADC1 RESULT register to the ADC_ConvertedValue[10] array of variables.
