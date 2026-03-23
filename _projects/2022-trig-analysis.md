---
layout: project
title: Nutcracker problem
description: Class project into the dimensions of a nutcracker
technologies: [MATLAB, python]
image: /assets/images/function-graph.png
---

As part of a project, we were instructed to figure out the dimensions of a nutcracker while using common force values and grip strength. 

Problem statment and objective: calculate the necessary dimensions of the nutcracker and come up with a design to make this task feasible and if not, suggesting a new model. 

Constraints and Input Parameters:
1. Load required to crack nut : 222.18 kg 
2. Grip Strength : 40 kg 
3. Size of nut : 0.02 m

Solution:
1. Draw a FBD.
2. Use the law of moments of equilibrium. 
3. Determine length ratio.
4. Determine height ratio. 

Using the diagram of a nutcracker : by taking the nutcracker 
joint as pivot point: 
1. ![Diagram]({{ "/assets/images/IMG_9077.png" | relative_url }}){style="width: 500px"}
    l(c)*F - l(n)*F(n) = 0 
    l(c)/l(n) = F(n)/F(i)
              = 222.18/40 = 5.55 

    Due to similar triangles:
            = H(c) = 5.55H(n)
                   = 5.55(2)
                   = 11.11cm

            = L(c) = 5.55(4)
                   = 22.22 cm 
                   
    Thus, the nutcracker needs to be 22 cm long with the 
    nut position 4 cm away from the joint with the distance 
    between the arms equal to 22.2 cm. 

Since it has a length of 22 cm, this will be pretty large,
 thus it will be very difficult to handle. 

So use of Linear Actuator: 

Given: IP65 Mini 
       Max Load - 169 lbs 
       Dimensions - stroke length = 1 inch 
                    closed length = 5.13 inches 

       Force to crack nut = 222.15 kg 
       Size of nut = 2 cm 

       using the same similar triangle from before: 
            l(c)/l(n) = 222.18/ (169/2.2)
            = 2.90  

        using l(n) = 4cm, l(c) = 11.59 cm
            l(c)/l(n) = h(c)/h(n)
            h(n) = (5.13*2.54)/2.9
                 = 4.49 cm 
        h(n) is greater than the size of the nut, but the
        design needs to have the closed position as h(n) = 2 cm 
        so the new design could be:





        ![Nutcracker FBD](/assets/images/IMG_9077.png)






