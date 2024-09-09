These files contain the numeric results for the shifts in the QNM frequencies. 
The name of the files has the format: “theory_domega_polarization_ll_mm_nn.txt”, where 

theory=cubic_even, cubic_odd, quartic_1, quartic_2, quartic_3 
polarization=plus, minus
(l,m)=angular numbers
n=overtone number (n=0 is the fundamental mode)

For instance: “quartic_1_domega_plus_l3_mm1_n2.txt” corresponds to the QNM shifts of the quartic_1 theory with (l,m,n)=(3,-1,2) and “plus” polarization.

The format of the files is as follows

\chi	Re(\delta\omega)	Im(\delta\omega)	Error[Re(\delta\omega)]	Error[Im(\delta\omega)]

The error is the difference with the prediction of one order less in the spin expansion, and it can take negative values since we are not taking the absolute value