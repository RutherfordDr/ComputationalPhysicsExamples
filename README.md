# ComputationalPhysicsExamples
Saved all Physics related scripts

        1) Julia Sets
                The Julia set is the set of points on the complex plane where the series below does not diverge. 

                                                𝑍𝑛+1= 𝑍𝑛^2+𝐶                                              (1.0)

                Here C is a constant in the complex plane, and 𝑍0, the initial value, is each point on the 
                complex plane.

                This script plots the Julia Set for any inputted complex value C and displays an image of it.
                It then plots the Julia Set for Z = Z^2 + 0.7885e^(i*a) where a ranges from 0 to 2pi, and then 
                makes a gif of the changing values. 

                ![Alt Text](https://github.com/RutherfordDr/ComputationalPhysicsExamples/blob/master/animationHighQuality.gif)
                References: ℎ𝑡𝑡𝑝://𝑝𝑎𝑢𝑙𝑏𝑜𝑢𝑟𝑘𝑒.𝑛𝑒𝑡/𝑓𝑟𝑎𝑐𝑡𝑎𝑙𝑠/𝑗𝑢𝑙𝑖𝑎𝑠𝑒𝑡/
