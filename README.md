# 2015-ESE519-AutoCare
Project Title: ICU in a Bag
https://www.youtube.com/watch?v=doXPgKhIpFc&feature=youtu.be

Team member: Joon Yi Koh and Hanjun Kim

Overview:
Project consists of two mbed, a heart rate sensor, a flow rate sensor, a stepper motor, and a syringe

One mbed interact with heart rate sensor while the other interact with flow rate sensor.
When heart rate is abnormal, the stepper motor will move the syringe automatically to input dosage. When the input dosage is greater than required dosage, stepper motor will stop and continue monitoring heart rate. If heart rate is still abnormal after certain period, stepper motor will input dosage again, but if heart rate return normal, the stepper motor will stop.

