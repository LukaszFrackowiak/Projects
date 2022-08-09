image_analyzer.nb is a script that allows us analyze a series of images of magnetic domain evolution. Script has few parts: we can select the appropriate part of the image, measure hysteresis loop as a value of mean intesnity vs applied external magnetic field, and can measure which and how many of squares (more about sqaures you can find https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.124.047203) has been switched


deposition_numerical.nb is a numercial model of material distribution from pure target in the magnetron sputtering equipment. More detail about model you can find in https://www.sciencedirect.com/science/article/abs/pii/S0304885321009185

deposition_distribution.nb is a extend of deposition_numerical script. It allows us to calculate concentration distribution of given material in the sputtered thin layers of alloy from two targets. In script we can measure alloys of RE-TM of RE= Tb or Gd and TM = Co, Fe, Co87.5Fe12.5. 

Update
Numerical part was also made in Python. Code is more pleasent to eyes. Additionally included part where we can calculate only one line for Y = 0
