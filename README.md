# Patella testbed

> Simplified platform for testing various models of knee mechanics

Implements simplified versions of the knee joint mechanism from the following musculoskeletal models:  
* Gait 2392 (Delp 1990++)
     * Yamaguchi knee + quadriceps with a moving point insertion acting directly on tibia
* Arnold 2010
     * Walker knee + quadriceps attaching on patella
* Rajagopal 2016
     * Walker knee + quadriceps wrapping over patella and inserting on tibia

Two versions of each model are included, one with a musculotendon actuator (because PathActuator moment arms are hard to plot), and one with the muscle converted to a PathActuator (for forward simulations)

 
