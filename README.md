# FourA-Data-Analytics-Project
Analysis of Traffic violations in Maryland County
Attriutes present and their meanings:
The data include items, such as:
----------------------------------------------------
Accident : If traffic violation involved an accident.
Agency : Agency issuing the traffic violation. (Example: MCP is Montgomery County Police)
Alcohol : If the traffic violation included an alcohol related
Arrest Type : Type of Arrest (A = Marked, B = Unmarked, etc.)
Article : Article of State Law. (TA = Transportation Article, MR = Maryland Rules)
Belts : If traffic violation involved a seat belt violation.
Charge : Numeric code for the specific charge.
Color : Color of the vehicle.
Commercial License : If driver holds a Commercial Drivers License.
Commercial Vehicle : If the vehicle committing the traffic violation is a commercial vehicle.
Contributed To Accident : If the traffic violation was a contributing factor in an accident.
Date Of Stop : Date of the traffic violation.
Description : Text description of the specific charge.
DL State : State issuing the Driver’s License.
Driver City : City of the driver’s home address.
Driver State : State of the driver’s home address.
Fatal : If traffic violation involved a fatality.
Gender : Gender of the driver (F = Female, M = Male)
Geolocation : Geo-coded location information.
HAZMAT : If the traffic violation involved hazardous materials.
Latitude : Latitude location of the traffic violation.
Location : Location of the violation, usually an address or intersection.
Longitude : Longitude location of the traffic violation.
Make : Manufacturer of the vehicle (Examples: Ford, Chevy, Honda, Toyota, etc.)
Model : Model of the vehicle.
Personal Injury : If traffic violation involved Personal Injury.
Property Damage : If traffic violation involved Property Damage.
Race : Race of the driver. (Example: Asian, Black, White, Other, etc.)
State : State issuing the vehicle registration.
SubAgency : Court code representing the district of assignment of the officer.
Time Of Stop : Time of the traffic violation.
VehicleType : Type of vehicle (Examples: Automobile, Station Wagon, Heavy Duty Truck, etc.)
Violation Type : Violation type. (Examples: Warning, Citation, SERO)
Work Zone : If the traffic violation was in a work zone.
Year : Year vehicle was made.
----------------------------------------------------
There are two datasets present in the repository. One which is the original dataset. And the other dataset was a result of dimensionality reduction.
The data had many inconsistencies and Nan values which were taken care of by using similarity tests and imputing the Nan values.
An extensive data visualization has also been done, which are self-explanatory. 
Since the dataset is a time series data, it was decomposed to study the trend and seasonality. We used SARIMA for predicting the values in the test set. A forecast has also been done for few months in 2018, and also 2019. The model was evaluated using MAPE.
