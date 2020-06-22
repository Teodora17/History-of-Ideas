# History-of-Ideas

2.1.2.1 Buildings
 
 	Other restrictions: 
R0: Only one value may be stored for impactScore. 
 	Domain restrictions:  
R1: impactScore  [0, 100];  
R5: yearReleased  [-1/1/3500, Date() ]  Date/Time;
R4: Building  ascii (64,91)+(96,123); 
Totality restrictions: 
R2:  impactScore, Country, yearReleased, Building mandatory;

2.1.2.1 Boooks
 
 	Other restrictions: 
R0: Only one value may be stored for impactScore. 
 	Domain restrictions:  
R1: impactScore  [0, 100];  
R5: yearReleased  [-1/1/3500, Date() ]  Date/Time;
R4: Country  ascii (64,91)+(96,123); 
R4: Language  ascii (64,91)+(96,123); 
R4: Book  ascii (64,91)+(96,123); 
Totality restrictions: 
R2:  impactScore, Country, yearReleased, Language, Books mandatory;

2.1.2.1 Compositions
 
 	Other restrictions: 
R0: Only one value may be stored for impactScore. 
 	Domain restrictions:  
R1: impactScore  [0, 100];  
R5: yearReleased  [-1/1/3500, Date() ]  Date/Time;
R4: Country  ascii (64,91)+(96,123); 
R4: Composition  ascii (64,91)+(96,123); 
Totality restrictions: 
R2:  impactScore, Country, yearReleased, Composition mandatory;

2.1.2.1 Paintings
 
 	Other restrictions: 
R0: Only one value may be stored for impactScore. 
 	Domain restrictions:  
R1: impactScore  [0, 100];  
R5: yearReleased  [-1/1/3500, Date() ]  Date/Time;
R4: Country  ascii (64,91)+(96,123); 
R4: Painting  ascii (64,91)+(96,123); 
Totality restrictions: 
R2:  impactScore, Country, yearReleased, Painting mandatory;

2.1.2.1 Films
 
 	Other restrictions: 
R0: Only one value may be stored for impactScore. 
 	Domain restrictions:  
R1: impactScore  [0, 100];  
R5: yearReleased  [-1/1/3500, Date() ]  Date/Time;
R4: Country  ascii (64,91)+(96,123); 
R4: Language  ascii (64,91)+(96,123); 
R4: Film  ascii (64,91)+(96,123); 
Totality restrictions: 
R2:  impactScore, Country, yearReleased, Film mandatory;

2.1.2.1 Sculptures
 
 	Other restrictions: 
R0: Only one value may be stored for impactScore. 
 	Domain restrictions: 
R4: Sculpture  ascii (64,91)+(96,123); 
R1: impactScore  [0, 100];  
R5: yearReleased  [-1/1/3500, Date() ]  Date/Time;
R4: Country  ascii (64,91)+(96,123); 
Totality restrictions: 
R2:  impactScore, Country, yearReleased, Sculpture mandatory;

 
 	2.1.2.2  Authors 
 
Other restrictions: 
R0: Only one value may be stored for Nationality, birthYear, deathYear, Alive?. 
 	Domain restrictions:  
R4: Author  ascii (64,91)+(96,123); 
R4: Nationality  ascii (64,91)+(96,123); 
R5: birthYear  [-1/1/3500, Date() ]  Date/Time;
R5: deathYear  [-1/1/3500, Date() ]  Date/Time;
R6: Alive?  {Yes, No}; 
 	Totality restrictions: 
R8: Nationality, birthYear, Alive?, Author mandatory;  	 
 
2.1.2.2  Composers
 
Other restrictions: 
R0: Only one value may be stored for Nationality, birthYear, deathYear, Alive?. 
 	Domain restrictions:  
R4: Composer  ascii (64,91)+(96,123); 
R4: Nationality  ascii (64,91)+(96,123); 
R5: birthYear  [-1/1/3500, Date() ]  Date/Time;
R5: deathYear  [-1/1/3500, Date() ]  Date/Time;
R6: Alive?  {Yes, No}; 
 	Totality restrictions: 
R8: Nationality, birthYear, Alive?, Composer mandatory;

2.1.2.2  Architects 
 
Other restrictions: 
R0: Only one value may be stored for Nationality, birthYear, deathYear, Alive?. 
 	Domain restrictions:  
R4: Architect  ascii (64,91)+(96,123); 
R4: Nationality  ascii (64,91)+(96,123); 
R5: birthYear  [-1/1/3500, Date() ]  Date/Time;
R5: deathYear  [-1/1/3500, Date() ]  Date/Time;
R6: Alive?  {Yes, No}; 
 	Totality restrictions: 
R8: Nationality, birthYear, Alive?, Architect mandatory;   

2.1.2.2  Painters
 
Other restrictions: 
R0: Only one value may be stored for Nationality, birthYear, deathYear, Alive?. 
 	Domain restrictions:  
R4: Nationality  ascii (64,91)+(96,123); 
R5: birthYear  [-1/1/3500, Date() ]  Date/Time;
R5: deathYear  [-1/1/3500, Date() ]  Date/Time;
R6: Alive?  {Yes, No}; 
 	Totality restrictions: 
R8: Nationality, birthYear, Alive? mandatory;  

2.1.2.2  Filmmakers
 
Other restrictions: 
R0: Only one value may be stored for Nationality, birthYear, deathYear, Alive?. 
 	Domain restrictions:  
R4: Nationality  ascii (64,91)+(96,123); 
R5: birthYear  [-1/1/3500, Date() ]  Date/Time;
R5: deathYear  [-1/1/3500, Date() ]  Date/Time;
R6: Alive?  {Yes, No}; 
 	Totality restrictions: 
R8: Nationality, birthYear, Alive? mandatory;  

2.1.2.2  Sculptors
 
Other restrictions: 
R0: Only one value may be stored for Nationality, birthYear, deathYear, Alive?. 
 	Domain restrictions:  
R4: Nationality  ascii (64,91)+(96,123); 
R5: birthYear  [-1/1/3500, Date() ]  Date/Time;
R5: deathYear  [-1/1/3500, Date() ]  Date/Time;
R6: Alive?  {Yes, No}; 
 	Totality restrictions: 
R8: Nationality, birthYear, Alive? mandatory;  

2.1.2.2  Proponents
 
Other restrictions: 
R0: Only one value may be stored for Nationality, birthYear, deathYear, Alive?. 
 	Domain restrictions:  
R4: Nationality  ascii (64,91)+(96,123); 
R5: birthYear  [-1/1/3500, Date() ]  Date/Time;
R5: deathYear  [-1/1/3500, Date() ]  Date/Time;
R6: Alive?  {Yes, No}; 
 	Totality restrictions: 
R8: Nationality, birthYear, Alive? mandatory;  

 	2.1.2.3 Name_of_concept 
 
 	Domain restrictions:  
R4: Name  ascii (0,23);  
 	Totality restrictions: 
R11: Name  mandatory; 
 	Uniqueness restrictions: 
R12: Name  unique;

	2.1.2.3 Characteristics 
 
 	Domain restrictions:  
R4: Description  ascii (0,123);  
 	Totality restrictions: 
R11:  Description mandatory; 
 	Uniqueness restrictions: 
R12: Description  unique;


2.1.2.3 Artistic_Current 
 
 	Domain restrictions:  
R4: Description  ascii (64,91)+(96,123);  
 	Totality restrictions: 
R11:  Description mandatory; 
 	Uniqueness restrictions: 
R12: Description  unique;

 
 	2.1.2.4 Historical_Period 
 
 	Domain restrictions:  
R5: startYear  [-1/1/3500, Date() ]  Date/Time;
R5: endYear  [-1/1/3500, Date() ]  Date/Time;
R4: Description  ascii (64,91)+(96,123);  
 	Totality restrictions: 
R15: startYear, Description mandatory;  	
Uniqueness restrictions: 
R16: Dates may coincide. 
 
2.1.2.4 Political_Conflicts 
 
 	Domain restrictions:  
R5: startYear  [-1/1/3500, Date() ]  Date/Time;
R5: endYear  [-1/1/3500, Date() ]  Date/Time;
R4: Description  ascii (64,91)+(96,123);  
 	Totality restrictions: 
R15: startYear, Description mandatory;  	
Uniqueness restrictions: 
R16: Dates may coincide. 

 	2.1.2.5 Political_Ideologies 
 
 	Domain restrictions:  
R17: Description  ascii (64,91)+(96,123); 
	Totality restrictions: 
R20: Description mandatory; 
 Uniqueness restrictions: R21: Description unique. 
 
 	2.1.2.6  Parties_Involved 
 
 	Domain restrictions:  
R17: Description  ascii (64,91)+(96,123); 
 	Totality restrictions: 
R25: Description mandatory;  	
Uniqueness restrictions: 
R26: There may not be 2 similar descriptions for parties. 

 	Other restrictions: 
R28:  For any subscription,  birthYear <= deathYear; 
R28:  For any subscription,  startYear <= endYear;
R29: No two descriptions may overlap. 
