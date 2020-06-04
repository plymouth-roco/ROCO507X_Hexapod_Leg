# ROCO507X_Hexapod_Leg

Abstract—This  paper  is  the  research  and  design  of  a  singlerobot  leg  for  mounting  and  use  on  a  hexapod  robot.  The  robotspecification  was  a  maximum  extended  length  of  30cm  and  tobe  able  to  withstand  a  3kg  mass  applied.  This  paper  involvesresearch into the theory of hexapods and the current applications,mathematical  analysis  into  compression  and  shear  forces,  thetheory  and  calculations  into  possible  damping  systems  for  theleg,  the  kinematics  and  programming  of  3  servo  motors  to  beable  to  correctly  move  the  leg  and  know  its  position  and  finallythe  design  and  testing  of  the  leg  through  fusion  360  and  fusion360 FEA. Unfortunately due to circumstance out of the authorshands  only  simulation  testing  could  be  performed

Introduction-
The  main  goal  of  this  project  was  to  design  and  build  asingle  leg  to  be  mounted  to  a  Hexapod.  The  design  makesconsideration  so  that  the  leg  can  be  used  as  a  template  forthe  additional  five  legs  of  a  Hexapod.  For  this  design  wealso had several constraints that we needed to consider duringthe  design  process,  which  was  that  the  leg  had  to  have  amaximum  extension  of  0.3m,  a  maximum  compression  of0.05m, be able to withstand a 3kg load and have a minimumof 3 degrees of freedom. Additionally, we wanted the Hexapodto  be  omnidirectional  with  a  full  3600  movement  range  andto keep costs low to allow for prototyping during our designprocess.From  our  research  we  had  identified  that  many  Hexapodshave  two  main  issues,  their  legs  slip  on  surfaces,  and  theirservos are weak to high impact shocks, which causes damageto the gear’s teeth. With this consideration taken we wanted todesign  a  dampening  system  that  would  increase  the  durationof time that an impact force was to act upon the Hexapod legin order to prevent the gears within the servos being damaged.In addition, we also wanted to design and test the foot of theleg  to  provide  a  solution  that  would  prevent  slipping  whentraversing terrain.To  complete  this  task  and  design  the  leg,  the  shear  andbuckling  forces  were  looked  into  along  with  the  kinematicsand  damping  mathematics.  Once  these  were  finished  and  anapproximation  for  the  required  dimensions  was  obtained  theleg  was  designed  on  fusion  360.  The  design  then  underwentFEA  testing  to  see  if  the  leg  could  withstand  the  forces  itwould experience during operation.The  paper  will  be  broken  down  into  the  current  sections,Section II - Mini literature review into hexapod, Section III -Mathematics  and  Design,  Section  IIII  -  Experimentation  andTesting, Section 5 - Discussion and Analysis and Section 6 -Conclusion


Videos of the project 
Hexapod 150N ABS Linera Load: https://youtu.be/3N0--9uB0ZQ  
Hexapod 30N ABS Linear Load: https://youtu.be/XNTOAyoOz1A  
Hexapod 30N ABS Axial Load: https://youtu.be/DyvUvr6EpBE  
Hexapod 150N Aluminium Foot Linear Load: https://youtu.be/gAU8AoaYmio  
Hexapod Leg Animation: https://youtu.be/sJPqHgT1XRM  
Hexapod Leg Animation Explode Parts: https://youtu.be/MlwZA7ifQns  


