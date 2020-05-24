# Pyber_Analysis Challenge 5

An analysis was performed on PyBer ride sharing data to determine the allocation of revenue, drivers, and ride counts. The three categories were filtered by city types consisting of Suburban, Rural, and Urban. The comparison between the three city types allows PyBer to understand the business details of the different areas and ultimately make decisions to increase future profits. The table below contains the complete comparison showing the ride data, driver count, total fares, and the corresponding averages on a rider and driver basis. It is seen that the Urban city types see most of the traffic, and the Rural cities receiving the least amount of traffic.

![](analysis/table.PNG)
 
A few challenges were experienced throughout this assignment. Firstly, the data frames were merged incorrectly resulting in the driver_count data to be incorrectly summed. This was fixed by pulling the driver_count data directly from the city_data spreadsheet. Next, the date was formatted using a object datatype and in order to perform mathematical operations to the dates, this would have to be converted into a DateTime format. This was achieved using a pd.to_datetime function within Pandas. Finally, the formatting of the final summary graphs revealed a fair amount of troubles. In order to achieve the desired chart format, the xticks and xticks labels had to be modified. A for loop was built to take every even number (incld 0) index from the origina xticks()[0] array, and then the labels were modified by utilizing an list with the desired labels inside. 

![](analysis/Fig8.PNG)

