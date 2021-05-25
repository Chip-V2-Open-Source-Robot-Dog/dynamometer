# The little "Dino" that CAN't

So one day we were in the solar car shop and found a dynamometer was was rated to 20Nm, now we definetly couldn't use something like this for our actual motors as our motors go up to at least 40Nm on solar car, but we definetly could use it for Chip! We want to do this for a few reasons. 

* First, for solar car we want to see if we can get a dyno setup that will measure the entire system losses including the VxI into the motor controller and the TxW out of the motor to get a system loss metric. We want to see if we can find a strategy to do that with this setup because then we can do a drop-in replacement with the larger system. 
* We want to use the dyno to see how well torque control works with the SparkMAX motors! 
* Find out NEO Motor Torque/speed data @ 24V as opposed to 12V.

We will use a lot of the same roborio firmware as the hoppy-leg test, we may do dyno before we do hoppy leg. The final code will be linked but until then only the python code will be linked for the dyno. 

LINKS:
https://www.interfaceforce.com/products/torque-transducers/rotary/t8-general-purpose-shaft-style-rotary-torque-transducer/

SOFTWARE:
https://www.interfaceforce.com/support/software-and-drivers/

### Updates

(Initial Stuff) https://www.adim.io/post/dyno-update-yes-a-dyno-updates

(Adi Confuses Himself) https://www.adim.io/post/dino-updates-initial-tests-w--datalogging-current-control-and-etc-updates

(Adi Confuses Himself More) https://www.adim.io/post/dino-control-updates-getting-new-interfaces-between-the-jetson-and-the-rio-updates

(We're Less Confused + Have a Better Plan) https://www.adim.io/post/dino-updates-talked-to-elijah-and-andrew-a-little-updates

(Woah... Progress) https://www.adim.io/post/dyno-updates-new-power-supply-e-stop-and-further-testing-updates

### Credits + References:

MIT Biomimetic Robotics Lab; 
Professor Sangbae Kim;
Elijah B. Stranger-Jones;
Quang Kieu; 
Name Credits: Fischer Moseley
