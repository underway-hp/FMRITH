***************************************Explanation of the Instance Data*****************************
RequestsNum:                                         
6                                                              // it denotes that "RequestsNum" has a value of 6
Requests and depot info:	           
ID	Loc_x		Loc_y		RdrNum	LugNum	EarTime	LatTime	DDL_Arr	TUB
0	121.430649	31.15344	0	0	0	1440	1440	1440	// this request denotes the depot
1	121.3272287	31.1807562	1	1	422	452	485	33	// this is the first request node
2	121.4048637	31.2609823	1	0	418	448	485	37	
3	121.4624585	31.2091887	2	1	440	470	495	25	
4	121.399733	31.2128983	1	0	441	471	495	24	
5	121.490314	31.1804742	1	1	428	458	480	22	// this is the last request node
									
DisMat:									                                                     //the unit of distance is meter
0	13397.114	13552.926	8233.017	8046.874	6767.904				
12403.789	0	14738.942	14997.235	9179.462	19077.421				
13355.703	15563.882	0	10061.968	6410.398	14599.979				
8915.132	16445.908	9799.47	0	7296.154	6161.779				
8013.214	10311.794	6633.941	7327.041	0	11672.669				
6790.243	20017.713	15002.254	5327.65	11963.454	0

//"RequestsNum" indicates the total number of nodes consisting of requests and a depot;

//"Requests and depot info" displays the detailed information about the depot and each request: 
////"ID" is the depot and requests number; 
////"Loc_x" and "Loc_y" are the longitude and latitude of this depot or each request; 
////"RdrNum" refers to the number of riders for each request;
////"LugNum" means the number of pieces of large luggage to be carried by each request;;
////"EarTime" and "LatTime"  denote the earliest and latest pickup time for each request, with a maximum value of 1440 minutes (each day contains 1440 minutes);
////"DDL_Arr" is the arrival deadline for each request;
////"TUB" is the maximum ride time of each request;

//"DisMat" is the distance matrix between nodes,  extracted by the Osmnx package.
