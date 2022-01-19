# Hotel-cancellation-analysis
Project for Syracuse University's School of Information Studies course IST687 (Introduction to Data Science)

## Goal of the project
* The	overall	goal	of	the	case	is	to	provide	actionable	insight,	based	on	the	data	available.
* The	dataset	contains	real-life	hotel	stay	data,	with	each	row	representing	a	hotel	booking.
* The main goal is	to	understand	some	key	drivers	for	why	people	cancel	hotel reservations and/or	better	predict	who	will	cancel.	To	do	this,	I used	all	of	the	skills I 	have	developed	in	the	course	to	make	sense	of	a	novel	dataset,	to	perform	some	essential	analyses	on	the	dataset,	and	to	explain/document	what	I	have	done, and	
my	insights	that were generated

## The Data:
Here	are	the	variables	you	will	find	in	the	data	file:
* IsCanceled:	Categorical	Value	indicating	if	the	booking	was	canceled	(1)	or	not	(0)		
* LeadTime:	Integer,	Number	of	days	that	elapsed	between	the	entering	date	of	the	
booking	into	and	the	arrival	date		
* StaysInWeekendNights:	Integer,	Number	of	weekend	nights	(Saturday	or	Sunday)	
the	guest	stayed	or	booked	to	stay	at	the	hotel		
* StaysInWeekNights:	Integer,	Number	of	week	nights	(Monday	to	Friday)	the	guest	
stayed	or	booked	to	stay	at	the	hotel		
* Adults:	Integer,	Number	of	adults		
* Children:	Integer,	Number	of	children		
* Babies:	Integer,	Number	of	babies	
* Meal:	Categorical,	Type	of	meal	booked.	Categories	are	presented	in	standard	
hospitality	meal	packages:		Undefined/SC	– no	meal	package;	BB	– Bed	&	Breakfast;		
HB	– Half	board	(breakfast	and	one	other	meal	– usually	dinner);		FB	– Full	board	
(breakfast,	lunch	and	dinner)		
* Country:	Categorical,	Country	of	origin.	Categories	are	represented	in	the	ISO	3155–
3:2013	format		
* MarketSegment:	Categorical,	Market	segment	designation.	In	categories,	the	term	
“TA”	means	“Travel	Agents”	and	“TO”	means	“Tour	Operators”		
* IsRepeatedGuest:	Categorical,	Value	indicating	if	the	booking	name	was	from	a	
repeated	guest	(1)	or	not	(0)		
* PreviousCancellations:	Integer,	Number	of	previous	bookings	that	were	cancelled	
by	the	customer	prior	to	the	current	booking		
* PreviousBookingsNotCanceled:	Integer,	Number	of	previous	bookings	not	
cancelled	by	the	customer	prior	to	the	current	booking		
* ReservedRoomType:	Categorical,	Code	of	room	type	reserved.	Code	is	presented	
instead	of	designation	for	anonymity	reasons		
* AssignedRoomType:	Categorical,	Code	for	the	type	of	room	assigned	to	the	
booking.	Sometimes	the	assigned	room	type	differs	from	the	reserved	room	type	
due	to	hotel	operation	reasons	(e.g. overbooking)	or	by	customer	request.	Code	is	
presented	instead	of	designation	for	anonymity	reasons		
* BookingChanges:	Integer,	Number	of	changes/amendments	made	to	the	booking	
from	the	moment	the	booking	was	entered	on	the	PMS	until	the	moment	of	check-in	
or	cancellation		
* DepositType:	Categorical,	Indication	on	if	the	customer	made	a	deposit	to	
guarantee	the	booking.	This	variable	can	assume	three	categories:	No	Deposit	– no	
deposit	was	made.	Non	Refund	– a	deposit	was	made	in	the	value	of	the	total	stay	
cost.	Refundable	– a	deposit	was	made	with	a	value	under	the	total	cost	of	stay.	
* CustomerType:	Categorical,	Type	of	booking,	assuming	one	of	four	categories:		
Contract	- when	the	booking	has	an	allotment	or	other	type	of	contract	associated	to	
it;	Group	– when	the	booking	is	associated	to	a	group;	Transient	– when	the	booking	
is	not	part	of	a	group	or	contract,	and	is	not	associated	to	other	transient	booking;	
Transient-party	– when	the	booking	is	transient,	but	is	associated	to	at	least	other	
transient	booking	
* RequiredCardParkingSpaces:	Integer,	Number	of	car	parking	spaces	required	by	
the	customer	
* TotalOfSpecialRequests:	Integer,	Number	of	special	requests	made	by	the	
customer	(e.g. twin	bed	or	high	floor)
