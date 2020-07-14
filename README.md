ESD is also known as Electrostatic Discharge.It is a part of EOS which we can say as Electrical Overstress.

What is Electrical Overstress-Any chip or device has a specification mentioned in the datasheet like the breakdown voltage or current or the Rds on the threshold voltage etc.If a chip is functionalised to a specification above the mentioned specifications for a long time then the chip might fail or in simple words get destroyed maybe internally or externally.It might also happen if we reach exact specifications mentioned in the datasheet the IC may get destroyed.In electrical or electronical world we say that the device under test or in use is under stress or overstress and from herewe term the same as electrical over stress(EOS). 

ESD is one of the main cause of EOS .It analogical to impulsive force, a huge force acting on a body for a very short time .Here the force is nothing but the voltage being generated internally or sometimes externally for very small period of time ,maybe for ns a voltage of a range of KV is generated .This will cause great damage to the chip.
An object is or in this case a IC is not vulnearble to ESD if it does not have any path for the discharge.Like for example a voltage is generated that means charges are accumulated in the IC circuitry and those charges dont have any path to get discharged then that IC is not ESD vulnerable.Hence for a ESD to occur the chip must be separated from a conducting body by a Resistance so that a potential difference is being created and a current flows thus causing discharge of the charges.

Various Models to measure the ESD is already in practise
1)HBM or Human Body Model- Here the Human body is modeled via a Resistance of 1500ohms a capaciatnce 100 pF .This whole circuitry is then connected with the DUT and tested.If the rise and time is of desired result then this ESD event is a pass .
2)MM or Machine model- The same theory is same but the model is now designed with R=100 Ohm, C= 200 Pf and L =0.5 nH .
3)Charged Device Model or CDM-The theory is the same but here the model is designed R=10-50 Ohm, C= 200 Pf and L =0.5 nH 

What we see is that the discharge is the fastest in the CDM and slowest in the HBM due to the resistance .
