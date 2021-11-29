An "RSVP" microstructure profiler was deployed at CEAREX O Camp over
the flanks of the Yermak Plateau, Eastern Arctic Ocean, in April 1989.
1377 profiles were obtained, most to ~350 m depth, at a typical sampling
rate of 2-3 profiles per hour.

The profiles recorded depth, temperature, conductivity (for salinity) and
dissipation rate of turbulent kinetic energy (epsilon), the latter calculated
from microstructure shear. See Padman and Dillon (1991) and Wijesekera et al.
(1993) for further details.

Data have been averaged to 1.0 m depth bins, 0-350 m. Note that epsilon is
stored as log10(epsilon); actual dimensional values (W/kg) are obtained as
eps=10^Epsg.

Inferred water depth is based on profile location using IBCAO 3.0.


File: CEAREX_RSVP.mat

File contents:

  Name               Size                Bytes  Class     Attributes
                 (depth x time)

  Epsg             350x1377            3855600  double    log_10(epsilon)          
  Sg               350x1377            3855600  double    Salinity       
  Tg               350x1377            3855600  double    Temperature          
  crx_SDtime         1x1377              11016  double    Profile time in Matlab 'datenum' (UTC)        
  crx_id             1x1377              11016  double    Profile number          
  crx_lat            1x1377              11016  double    Latitude          
  crx_lon            1x1377              11016  double    Longitude  
  crx_name           1x1377             176256  cell      Original file name          
  crx_t1989          1x1377              11016  double    Profile time, decimal day 1989 **         
  sigg             350x1377            3855600  double    sigma_theta          
  water_depth        1x1377              11016  double    water depth (inferred)          
  zg                 1x350                2800  double    data depth vector (1-350 m)          

** crx_t1989 is such that Jan 1, 1989, 12:00 => crx_t1989=0.5


References

Padman, L., & Dillon, T. M. (1991). Turbulent mixing near the Yermak 
Plateau during the coordinated Eastern Arctic Experiment. Journal of 
Geophysical Research: Oceans, 96(C3), 4769-4782.

Wijesekera, H., Padman, L., Dillon, T., Levine, M., Paulson, C., & 
Pinkel, R. (1993). The application of internal-wave dissipation models to a
region of strong mixing. Journal of physical oceanography, 23(2), 269-286.