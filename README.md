# GGE-6102-Quantitative Analysis in Geomatics

Assignment 2 
Applying filtering exclusively to vertical position data located in .csv file "962002Data.csv" that contains position data for a Canadian active GNSS station, and includes time(date); north, east, and vertical coordinates; and status. 

The filters used include;
Moving average with 1-week, 2-week, and 4-week windows;
Simple FIR filter with 25%, 50%, and 75% gain;
Gaussian filter with sigma = 3, 7, and 14;
FIlter using least square spectral analysis (LSSA) for periods of; 7 days or lower, 14 days of lower, 8 days or higher, 15 days and higher, and 10 to 40 days inclusive;
	
	
The following questions were posed to compare and assess the results and requirements of the filters applied;
1. What periodic trends can you identify in the data? What are their apparent frequencies and amplitudes?
	
2. What are the strengths and weaknesses of each type of filter?
	
3. For the filters in 1 and 3, how are the parameters of the filter related to the period of signals retained and filtered out?
	
4. Describe a hypothetical situation where you would want to use a low pass, band pass, and high pass filter.

