# battest
Battery testing programs
Different testing program settings in .txt format. This format can be openened with Biologic BT-lab or EC-lab cell cyling software directly. The first half of the filename refers to the type of test. These types are formation, rate, reference cycles, galavanostatic intermittent titration technique (GITT) and staircase-GITT (sGITT). 

The second half contains extra information on specific settings. "A" and "T" mean test for anode half cell and three electrode cell respectively. "C" and "D" indicate if the test is testing (fast) charge or discharge capability respectively. "P" indicates if a predelithiation step is added before the rest of the test is started. "R" indicates that the data is collected at high resolution. "E" indicates whether the test is combined with PEIS tests. "####V" indicates the voltage window. '##C' indicates the maximum C-rate used in the test.

Each test program is optimised for ideal sample rate, such that transient regions are sampled with a higher sample rate than steady state regions.
