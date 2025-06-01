# TridentTechProjects
School projects with Python code

#Project 1 (Calculation of a trucks weight)

Assumptions
One run of trucks
small truck = 5 tons
large truck= 10 tons

Input
smallTruck
largeTruck
perTonsRate

Calculations
smallTruckTons = smallTruck * 5
largeTruckTons = largeTruck * 10
totalTons = smallTruckTons + largeTruckTons
bill = totalTons * perTonsRate

Output
smallTruckTons
largeTruckTons
totalTons
bill
smallTruckWeight = 5
largeTruckWeight = 10


Input: numSmallTrucks
Input: numLargeTrucks
Input: numTonRate


smallTruckTons = numSmallTrucks * smallTruckWeight
largeTruckTons = numLargeTrucks * largeTruckWeight
totalWeight = smallTruckTons + largeTruckTons
bill = totalWeight * numTonRate

Output: smallTruckTons
Output: largeTruckTons
Output: totalWeight

Project #2 (Calculation discounts)
Assumptions
Only one discount can be used. 
Only the highest discount can be available for the customer
Customer can qualify for all uses
No sales tax if over 90
employee rate = 10%
contractor rate = 20%
order rate = 5%
tax rate = 8%


Input
Goods price
Discount Type (1.Employee, 2 Neither, 3 Contractor, 4 Both)
Age


Calculations

discount price = discount rate * goods price
subtotal = goods price - discount price
Sale Tax Price = sales tax * subtotal
final bill = sales tax price + subtotal
if (discount type > 2)
	discount rate = contractor rate
else if (discount type < 2)
	discount rate = employee rate
else (goods price > 800)
	discount rate = order rate


Project 3 (Calculating vehicle type and cost)

Assumptions
fordLow = 2%
fordMid = 3%
fordHigh = 5%
gmLow = 5%
gmMid = 7%
gmHigh = 10%
dodgeLow = 1%
dodgeMid = 2%
dodgeHigh = 3%

lowCutOff =  10,000
highCutOff = 20,000

Input
vehicleType
Cost

if vehicleType = "Ford"
	markupLow = fordLow
	markupMid = fordMid
	markupHigh = fordHigh

else if vehicleType = "GM"
	markupLow = gmLow
	markupMid = gmMid
	markupHigh = gmHigh

else if vehicleType = "Dodge"
	markupLow = dodgeLow
	markupMid = dodgeMid
	markupHigh = dodgeHigh
else

if cost < lowCutOff
	markupRate = markupLow
else if cost > highCutOff
	markupRate = markupHigh
else
	markupRate = markupMed

markup = cost * markupRate
final price = cost + markup

Output
vehicleType
cost
final price

Project 4 (Calculating number of tickets and cost )

Assumptions
Can only buy one type of ticket
Number of tickets is unlimited
upper level ticket = 10
lower level ticket = 30
floor ticket = 40
orchestra ticket= 50


Input
Section Type
Number of Tickets



Calculation

if (section type = orchestra )
	ticket cost = number of tickets * orchestra ticket
else if (section type = floor )
	ticket cost = number of tickets * floor ticket
else if (section type = lower level ticket)
	ticket cost = number of ticket * lower level ticket
else
	ticket cost = number of ticket * upper level ticket

Output

Number of Tickets 
Ticket Cost

ticket cost = number of tickets * section





Output: bill
