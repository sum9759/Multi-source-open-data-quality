# Multi-source-open-data-quality

The	objective	of	the	project	is	to	create	a	complete	and	clean	dataset	of	playing	pitches	around	Dublin	region.	 The	resulting	dataset	should	be	a	csv	file	containing	as	much	
informative	columns	as	possible.	 

Input	datasets:
Dataset	are	available	on	https://data.gov.ie
- [DCC]	Playing	pitches	in	Dublin	City	Council:	https://data.gov.ie/dataset/dublin-citycouncil-parks-playing-pitches
- [DLR]	Playing	pitches	in	DLR:	https://data.gov.ie/dataset/dlr_pitches
- [F]	Playing	Pitches	in	Fingal:	https://data.gov.ie/dataset/playing-pitches

Data	format:
Each	of	these	datasets	exhibits	resources	using	various	format:	csv,	xml,	kml,	html,	etc. You	
should	use	at	least	2	different	formats (you	will	need	to	manage	3	files	with	at	least	2
different formats).

Methodology:
You	will	have	to	create	the	resulting	dataset	by	merging	three	different	resources	by	
resolving	the	following	the	three-step	pipeline	introduced	in	the	lecture:
- Step1:	Observation. Perform	an	observatory	analysis	of	the	datasets	and	define	a	
data	management	plan	for	creating	the	resulting	dataset.
- Step	2: Data	modelling:	Create	a	unified	model	that	should	include	the	resulting	
fields	of	each	record	in	your	dataset.	The	minimal	fields	required	are:	location,	and	
geographical	coordinates	(use	x	and	y).
- Step	3: Data	Quality	Enhancement:	You	will	be	faced	with	two	main	challenges:
o Data	cleaning	challenge:	Merge	the	input	resource	and	make	sure	that	there	
are	no	duplicates,	Locations	can be	created	by	merging	various	fields,	etc.
o Incomplete	data	challenge: The	first	dataset [DCC] does	not	have	any	
geographical	coordinates.	A	solution	to	complete	this	information	is	required
