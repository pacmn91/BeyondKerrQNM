These files contain the fits to the shifts in the QNM frequencies as a function of the rotation parameter \chi 
The name of the files has the format: “theory_polarization_ll_mm_nn.txt”, where 

theory=cubic_even, cubic_odd, quartic_1, quartic_2, quartic_3 
polarization=plus, minus
(l,m)=angular numbers
n=overtone number (n=0 is the fundamental mode)

For instance: “quartic_1_plus_l3_mm1_n2.txt” corresponds to the QNM shifts of the quartic_1 theory with (l,m,n)=(3,-1,2) and “plus” polarization.

The format of the files is as follows

k	Re(c_k)	Im(c_k)

where c_k are the coefficients of the fit, defined as \delta\omega=\sum_{k=0}^{k_{max}}c_{k}\chi^k