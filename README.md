The calculation was based on the method described in https://book.magneticearth.org/geomag-obs-models/02a_k-index-calculation#:~:text=To%20derive%20a%20K%2Dindex,D%20and%20H%20'winning'. I just rescale it for the continuous time interval.

Data source: NOAA GOES database

File Description:

int_pr.csv : GOES-16 integrate proton flux data

int_el.csv : GOES-18 integrate electron flux data

magneto.csv : GOES-16 Magnetometer data

head.csv : list of NOAA database URL

get_data.ipynb : update data by Selenium

k_index.ipynb : plot raw magneto field - K index - int. proton flux - int. electron flux data as Sum.pdf


