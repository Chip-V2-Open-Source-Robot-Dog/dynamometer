# Two-Motor Dyno System

So one day we were in the solar car shop and found a dynamometer was was rated to 20Nm, now we definetly couldn't use something like this for our actual motors as our motors go up to at least 40Nm on solar car, but we definetly could use it for Chip! We want to do this for a few reasons. 

* First, for solar car we want to see if we can get a dyno setup that will measure the entire system losses including the VxI into the motor controller and the TxW out of the motor to get a system loss metric. We want to see if we can find a strategy to do that with this setup because then we can do a drop-in replacement with the larger system. 
* We want to use the dyno to see how well torque control works with the SparkMAX motors! 

We will use a lot of the same roborio firmware as the hoppy-leg test, we may do dyno before we do hoppy leg. The final code will be linked but until then only the python code will be linked for the dyno. 
