This is a code made for Bicopter with combined servos for roll, pitch and yaw movement and stabilization. 
The components used are MG995-SERVOS, BLDC , ESP8266 Nodemcu , MPU-6050, PCA-9685  and for rc i've used FLY-SKY FSi6 6 channel.
from this library you can customize the code for any configuration, for ease of connectivity i used pca9685 module for servo controll thus it can be controlled via I2C protocols.
the first code is for uav stabilization only by mpu values and rc is not included. if rc is needed, code can be changed in the pwm.setpwm command and pitch,roll and error can be reconfigured based on rc inputs.

