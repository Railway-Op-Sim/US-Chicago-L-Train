# Chicago 'L' Train

This is a complete rendition of the Chicago subway network known locally as the 'L' train. All of the eight major lines are included with all stations and a few of the depots. This is an advanced simulation not for those who are only just getting used to the software/the signalling of services, although much of the route has been automated all the major junctions require setting manually, it will be hard! You should definitely read this README before getting started. 

The included timetable runs between 6am and 7am and has all services between these times. Some manoevures are 'guessed' but all in all the output is very close to reality. The session has all crossovers set automatically, firstly to reduce the chance of the user going mad with the constant flashing of trains reporting being held up, and secondly to make it easier to identify the direction of services. 


## Quick Advice

- Set the Train Info to be on, DO monitor where each service needs to call at.
- Turn on the general service info window!
- I highly recommend leaving the session speed as half to begin with, increase only once you are confident.
- DON'T PANIC! This simulation is, as I say throughout, very hard!

## Station Names

This point warrants its own section. Unusual to many subways/railways across the world, the CTA subway actually has multiple stations sharing the same name! Stations are usually named after a road and as roads span a large distance this regularly leads to multiple stations en route. The limitations of Railway Operation Simulator mean it is not possible to have duplicates, which is probably a good thing considering the confusion this would cause! I have followed the covention used on CTA timetables whereby the name of the destination of a route is used within the station name, for example 'Jackson-O'Hare' resides on the Blue Line to O'Hare and 'Jackson-95th' on the Red Line to 95th/Dan Ryan. Another limitation of the simulator is that stations cannot be named using numbers as a first character (understandable given that coding variables ban this!), to cover these stations I have added an abbreviation of the route name, e.g. 'GL 43rd' for the Green Line's 43rd street station.

## The Network

The Chicago Transit Authority (CTA) operates eight routes across the network of tracks which make up the 'L' train. The subway is unique in having an elevated loop section located within downtown Chicago. Note that the routes passing through the Loop can be anti-clockwise or clockwise (or in the case of the Green Line only half the loop) but not both, i.e. the same route does not operate in both directions through the Loop! The eight routes that form the CTA subway are:

- Red Line: Howard to 95th/Dan Ryan
- Purple Line: Linden to Howard (Linden to Loop during peak times - as in the included session)
- Green Line: Harlem/Lake to Cottage Grove or Ashland/63rd (services alternate)
- Brown Line: Kimball to Loop
- Blue Line: O'Hare to Forest Park
- Orange Line: Midway to Loop
- Yellow Line: Dempster-Skokie to Howard
- Pink Line: Cermak/54th to Loop

this information is repeated within the simulation, and sections that are used exclusively for one route are also marked.


## Service Details

### Yellow Line

The Yellow Line, also known as the 'Skokie Swift' operates a short service from Dempster-Skokie to Howard. At the D-Skokie end services enter the north platform and then turn around at Dempster Headshunt before returning to Howard via the southern platform. At Howard the process is repeated with trains arriving at Howard platform 2, and then terminating at Howard Headshunt before then forming a new service which then picks up passengers at Howard platform 4. A total of two trains operate the route as a shuttle. Yellow trains are given the prefix 'YL' in the simulation.


### Pink Line

The Pink Line operates from Cermak/54th towards the Loop within the city. Unlike all other stations on the network Cermak/54th has two platforms that are positioned along the same line. Trains arriving here terminate on the west platform and are then directed around Cermak loop into the east platform before returning to the Loop. Within the Loop services pass through the eight stations clockwise. Pink trains are given the prefix 'PK' in the simulation.


### Red Line

The Red Line operates from Howard north of the city towards 95th/Dan Ryan in the south. It does NOT pass within the loop. Trains call at all stations between Howard and Belmont, then only at Fullerton before entering the tunnels under the city. As such these services should be directed onto the central two routes when leaving Howard station.

For trains to turn around at Howard, Howard Loop is used. Red Line services arriving at Howard should be directed from line 3 at Jarvis, to line 4 at Howard. They then proceed via the loop to line 1 where services commence again at Howard before passing into Jarvis via line 2. At 95th/Dan Ryan trains simply enter the station and change direction within the station limits. Red trains are given the prefix 'RD' in the simulation.


### Purple Line

Outside of rush hour Purple Line services usually commence at Linden and terminate at Howard. However the included simulation covers the morning rush hour period when these services are instead extended into the Loop. Trains approaching Howard should therefore be routed into platform 2 and then cross over onto line 1 to then proceed non-stop to Belmont, then calling at Wellington, Diversey, Fullerton and Armitage before diverging towards Sedgwick. Within the Loop trains proceed anti-clockwise starting at Washington/Wells. Purple trains are given the prefix 'PL' in the simulation. Four Purple services commence at Howard and are formed of empty stock labelled with the prefix 'HD' leaving Howard Yard East, these services should be directed into Howard platform 2 where they commence heading towards Linden.


### Blue Line

The Blue Line runs firstly from Chicago O'Hare international airport west of the city towards the city centre before then heading west again towards Forest Park. The route is about 90% automated with the controller only needing to concern themself with routing services into the platforms at O'Hare. At the Forest Loop end services are automatically routed into the loop where they terminate and recommence. Blue trains are given the prefix 'BL' within the simulation.


### Brown Line

The Brown Line runs from Kimball west of Chicago towards the Loop. Trains entering Kimball require routing from Kedzie-Kimball. Brown Line trains join the main line at Belmont where they must then call at all stations between Belmont and Sedgwick being routed into the city by line 1, and back via line 4. Brown Line trains pass through the Loop in an anti-clockwise direction the same as Purple Line trains. Brown trains are given the prefix 'BR' within the simulation.


### Green Line

The Green Line runs from Harlem/Lake, where services terminate and change direction within the platform, and either Cottage Grove or Ashland/63rd. These services pass through only the northern half of the Loop, entering at Clark/Lake from the west and exiting clockwise at Adams/Wabash heading south. To aid in directing services for trains heading south a prefix of either 'GC' or 'GA' is used for 'Cottage Grove' and 'Ashland/63rd', all other Green trains are given the prefix 'GR' within the simulation.


### Orange Line

The Orange Line runs from Midway airport to the Loop. Services change directions at Midway within the platform, and pass through the Loop in a clockwise direction from the south calling at Harold Washington Libary State/Van Buren first. Two services commence at Midway formed from empty stock allocated the prefix 'MD' from Midway Yard.



## Difficulty

I feel I should put this section in just as comfort. The simulation is hard!! Do not take it to be failure if you make a bad decision, even I have done so many times during testing. I have deliberately set the session to be half time to make it easier, if you feel things are still not going well DO reduce the rate further. Having said that I hope it is an enjoyable preview of the hustle and bustle around the windy city!
