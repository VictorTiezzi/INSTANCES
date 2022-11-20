Vehicle routing problem with simultaneous pickup and delivery (VRPSPD)

The subdirectory INSTANCES contains the following benchmark instances:

	DETHLOFF (40 instances)
	Source:
	Dethloff, J.:
	Vehicle routing and reverse logistics: the vehicle routing problem with
	simultaneous delivery and pick-up.
	OR Spektrum, 23(1):79-96 (2001)
	https://doi.org/10.1007/PL00013346

	GEHRING (20 instances)
	Source:
	Gehring, H., Homberger, J.:
	A parallel hybrid evolutionary metaheuristic for the vehicle routing problem
	with time windows.
	In: Proceedings of EUROGEN99:57–64 (1999)
	https://doi.org/10.1016/S0305-0548(03)00163-1

	RIECK
		R1 (100 instances)
		R2 (8 instances)
		R3 (25 instances)
		R4 (12 instances)
		R5 (18 instances)
		R6 (40 instances)
		R7 (2 instances)
	Source:
	Rieck, J., Zimmermann, J.:
	Exact Solutions to the Symmetric and Asymmetric Vehicle Routing Problem with
	Simultaneous Delivery and Pick-Up.
	German Academic Association for Business Research, 6(1):77-92 (2013)
	https://doi.org/10.1007/BF03342743

	SALHI (70 instances)
	Source:
	Salhi, D., Nagy, G.:
	A cluster insertion heuristic for single and multiple depot vehicle routing 
	problems with backhauling.
	Journal of the Operational Research Society 50, 1034–1042 (1999), 1034-1042
	https://doi.org/10.1057/palgrave.jors.2600808

PICKUP_AND_DELIVERY_SECTION :
Each line is of the form

      <integer> <integer> <real> <real> <real> <integer> <integer>

The first integer gives the number of the node.
The second integer gives its demand (ignored).
The third and fourth number give the earliest and latest time for the node.
The fifth number specifies the service time for the node.
The last two integers are used to specify pickup and delivery. The first of
these integers gives the size of the pickup, whereas the second integer gives
the size of the delivery.

The subdirectory TOURS contains the best tours found by LKH-3.

Tabulated results can be found in the subdirectory RESULTS.