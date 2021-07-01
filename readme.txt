=====================================================================
FFMPF CODE
=====================================================================
This FFMPF code achieves the fast forward modeling of potential field using the Trellis-based method.

   AUTHORS:

       Ju Fan
       Key laboratory of Petroleum Resources Research, Institute of Geology and Geophysics, Chinese Academy of Sciences, Beijing, China
       Email: fanju@mail.iggcas.ac.cn

       Ya Xu 
       Key laboratory of Petroleum Resources Research, Institute of Geology and Geophysics, Chinese Academy of Sciences, Beijing, China
       Email: xuya@mail.iggcas.ac.cn

   REFERENCE:

       The fast forward of potential field with the Trellis-based method
       


   SOFTWARE LANGUAGE:

       MATLAB (R2016b)

=====================================================================
CODE UPDATES AND BUG FIXES
=====================================================================

The code updates and bug fixes will be supported in the GitHub code repository

  https://github.com/Fan022/FFMPF

=====================================================================
PROGRAMS
=====================================================================

The FFMPF code consists two main programas and several subprograms:
============================main program=============================
model1_test.m              - calculating the potential field components                            
                             of Model 1.                             
model2_test.m  			   - calculating the potential field components                            
                             of Model 2.  		 
============================subprogram=============================== 
v.m                        - calculating the gravitational potential
                             using the traditional method
v_fast.m 				   - calculating the gravitational potential
                             using the Trellis-based method
vx.m                       - calculating the the first-order derivative of
                             gravitational potential in x direction 
							 using the traditional method
vx_fast.m 				   - calculating the the first-order derivative of
                             gravitational potential in x direction 
                             using the Trellis-based method	
vy.m                       - calculating the the first-order derivative of
                             gravitational potential in y direction 
                             using the traditional method
vy_fast.m 				   - calculating the the first-order derivative of
                             gravitational potential in y direction 
                             using the Trellis-based method	
vz.m                       - calculating the the first-order derivative of
                             gravitational potential in z direction 
                             using the traditional method
vz_fast.m 				   - calculating the the first-order derivative of
                             gravitational potential in z direction 
                             using the Trellis-based method	
vxx.m                      - calculating the the second-order derivative of
                             gravitational potential in x direction 
                             using the traditional method
vxx_fast.m 				   - calculating the the second-order derivative of
                             gravitational potential in x direction 
                             using the Trellis-based method	
vyy.m                      - calculating the the second-order derivative of
                             gravitational potential in y direction 
                             using the traditional method
vyy_fast.m 				   - calculating the the second-order derivative of
                             gravitational potential in y direction 
                             using the Trellis-based method	
vzz.m                      - calculating the the second-order derivative of
                             gravitational potential in z direction 
                             using the traditional method
vzz_fast.m 				   - calculating the the second-order derivative of
                             gravitational potential in z direction 
                             using the Trellis-based method	
vxy.m                      - calculating the the second-order derivative of
                             gravitational potential in x and y direction 
                             using the traditional method
vxy_fast.m 				   - calculating the the second-order derivative of
                             gravitational potential in x and y direction 
                             using the Trellis-based method	
vxz.m                      - calculating the the second-order derivative of
                             gravitational potential in x and z direction 
                             using the traditional method
vxz_fast.m 				   - calculating the the second-order derivative of
                             gravitational potential in x and z direction 
                             using the Trellis-based method	
vyz.m                      - calculating the the second-order derivative of
                             gravitational potential in y and z direction 
                             using the traditional method
vyz_fast.m 				   - calculating the the second-order derivative of
                             gravitational potential in y and z irection 
                             using the Trellis-based method								 
u.m                        - calculating the magnetic potential
                             using the traditional method
u_fast.m 				   - calculating the magnetic potential
                             using the Trellis-based method	
hx.m                       - calculating the the first-order derivative of
                             magnetic potential in x direction 
                             using the traditional method
hx_fast.m 				   - calculating the the first-order derivative of
                             magnetic potential in x direction 
                             using the Trellis-based method	
hy.m                       - calculating the the first-order derivative of
                             magnetic potential in y direction 
                             using the traditional method
hy_fast.m 				   - calculating the the first-order derivative of
                             magnetic potential in y direction 
                             using the Trellis-based method	
hz.m                       - calculating the the first-order derivative of
                             magnetic potential in z direction 
                             using the traditional method
hz_fast.m 				   - calculating the the first-order derivative of
                             magnetic potential in z direction 
                             using the Trellis-based method	
t.m                        - calculating the gravitational potential
                             using the traditional method
t_fast.m 				   - calculating the gravitational potential
                             using the Trellis-based method	
tx.m                       - calculating the the first-order derivative of
                             total field anomaly in x direction 
                             using the traditional method
tx_fast.m 				   - calculating the the first-order derivative of
                             total field anomaly in x direction 
                             using the Trellis-based method	
ty.m                       - calculating the the first-order derivative of
                             total field anomaly in y direction 
                             using the traditional method
ty_fast.m 				   - calculating the the first-order derivative of
                             total field anomaly in y direction 
                             using the Trellis-based method	
tz.m                       - calculating the the first-order derivative of
                             total field anomaly in z direction 
                             using the traditional method
tz_fast.m 				   - calculating the the first-order derivative of
                             total field anomaly in z direction 
                             using the Trellis-based method	
							 		 