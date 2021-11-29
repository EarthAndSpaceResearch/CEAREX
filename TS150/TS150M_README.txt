MicroCat sensor S/N 40 was deployed at CEAREX O Camp with first record 
at 22:00, 07-April-1989 UTC, recording every 1 minute, at a nominal
depth of 150 m.

File: TS150M.dat

Contains 10 header lines, followed by triplets of Temp (C), 
Conductivity (mmho/cm), Salinity (%)

Matlab function TS150M_read.m reads these data into a structure
function 'D', with time in Matlab "datenum" form.
