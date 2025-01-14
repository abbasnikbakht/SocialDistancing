## Data updates log

### April 9, 2020 (10:32 am PST)  
_Updated policy dataset pushed; documentation of updates in-progress._ 

### April 8, 2020 (9:15 am PST)  
**_Variable updates_**  
Starting today, we added one new category under "StatePolicy": "TravelRestrictEntry". Its description is below, as well as on the landing page README file.        
- **TravelRestrictEntry**: Travel restriction mandates that limit non-residents from entering a given state. These policies may have exceptions or exemptions for essential businesses or their employees, and they may include restrictions for commercial lodging for non-residents.

**_State updates_**  
- **Arizona**: "Quarantine" issued on 20200407, enacted on 20200409. This policy involves as 14-day quarantine for any individual entering Arizona from New York, New Jersey, and Connecticut as their points of travel origin.    
- **Arkansas**: "TravelRestrictEntry" issued on 20200404, enacted on 20200406.    
- **South Dakota**: "GathRestrict10" issued and enacted on 20200406, current expiry is 20200531. Because South Dakota had not issued a formal gather restriction mandate previously (their prior orders were recommendations), this policy also has been coded as "GathRestrictAny" with the same dates of issuance, enactment, and expiry.     
- **Wyoming**: "Quarantine" issued and enacted on 20200403, current expiry is 20200430. This policy involves a 14-day quarantine for any individual entering Arizona from any point of travel origin.


### April 7, 2020 (12:27 am PST)  
**_State Updates_**  
- **South Carolina**: "StayAtHome" issued on 20200406, enacted on 20200407.

### April 6, 2020 (12:48 pm PST)  
**_State Updates_**   
- **Delaware**: "Quarantine" issued on 20200329, enacted on 20200330.    
- **Delaware**: Revised "EnactDate" for "GathRecomAny" to 20200313; original entry was 20200316.  
- **Michigan**: Notes included on "SchoolClose" extension (i.e., an executive order has now closed schools through the end of the school year).

### April 5, 2020 (10:12 am PST)  
**_State Updates_**    
- **Nebraska**: "SchoolClose" issued and enacted 20200403, current expiry date is 20200531.    
- **Oklahoma**: "EmergDec" (state health emergency) issued and enacted 20200402, current expiry date is 20200502. This is the second declaration for Oklahoma, which issued is first emergency declaration on 20200402.

### April 4, 2020 (11:55 am PST)  
_Updated policy dataset pushed; documentation of updates in-progress._ 

### April 3, 2020 (8:48 am PST)  
**_Variable updates_**  
Starting today, we added three new categories under "StatePolicy": "Quarantine", "TravelRestrictIntra" and "TravelRestrictExit". Their descriptions are below, as well as on the landing page README file.    
- **Quarantine**: Quarantines on people entering the state, requiring a period of self-isolation. Quarantines may be imposed on all people entering the state, out-of-state residents, or travelers from a particular state or city. Quarantine length and who is covered by the policy can be found in the "PolicyNotes" column.   
- **TravelRestrictIntra**: Restrictions on travel within the state. These restrictions can be between cities or counties or within them. The "StateWide" column indicates whether these restrictions are in place throughout the state or only in local areas.  
- **TravelRestrictExit**:  Policies which prohibit residents of a state from leaving that state.  These policies may have exceptions for essential businesses.

**_State Updates_**  
- **Georgia**: "StayAtHome" issued 20200402, enacted on 20200403.  
- **Illinois**: Expiry date of 20200407 added for "StayAtHome" order.  
- **Tennessee**: "StayAtHome" issued 20200402, enacted 20200402.  
- **Quarantine**: In place in Alaska, Florida, Hawaii, Kentucky, Massachusetts, Montana, New Mexico, Rhode Island, South Carolina, Texas, Vermont, West Virginia.  
- **TravelRestrictIntra**: In place in Alaska.  
- **TravelRestrictExit**: In place in Kentucky. 


### April 2, 2020 (4:29 pm PST)  
**_Data in-progress updates_**  
Our team is currently adding quarantine, as well as intra- and interstate travel restrictions, policies to our development database. We plan to include these under "StatePolicy" in the immediate future.

**_State updates_**  
_Full documentation is in-progress for April 2_

### April 1, 2020 (9:10 am PST)  
**_State updates_**
- **Alabama**: "OtherBusinessClose" issued 20200327, enacted on 20200328. This was not coded as "NEBusinessClose" because it listed a subset of groups of non-essential businesses to close rather than issuing a full closure mandate and detailing exceptions.    
- **Arizona**: "StayAtHome" issued 20200330, enacted on 20200331.    
- **Connecticut**: Fixed typo for "StatePolicy": was "StateAtHome" now revised to "StayAtHome".    
- **Florida**: "NEBusinessClose" issued and enacted on 20200330 for subset of counties. StateWide==0.
- **Idaho**: "SchoolClose" issued and enacted on 20200323. This was previously not coded as a full school closure; re-review indicated that the soft-closure involved requiring all students to not attend school in-person and schools move to distancing learning, constituting a state-wide school closure.    
- **Mississippi**: "StayAtHome" issued and enacted on 20200331 for Lauderdale County only. StateWide==0.     
- **Mississippi**: "NEBusinessClose" issued and enacted on 20200331 for Lauderdale County only. StateWide==0.    
- **Pennsylvania**: "StayAtHome" issued and enacted on 20200328 for Beaver, Centre, and Washington Counties. StateWide==0.  
- **South Carolina**: "OtherBusinessClose" issued and enacted on 20200331. Similar to the Alambama order, this was not coded as "NEBusinessClose" because it listed a subset of groups of non-essential businesses to close rather than issuing a full closure mandate and detailing exceptions.    
- **Tennessee**: "StayAtHome" recommendation (Mandate==0) issued on 20200330, enacted on 20200401. The order urges all persons in Tenneessee to stay at home rather than mandating them to do so, so this is not currently coded as a "StayAtHome" mandate.    
- **Tennessee**: "NEBusinesClose" issued on 20200330, enacted on 20200401.    


### March 30, 2020 (4:17 pm PST)  
**_File updates_**
- Added "Mandate" to reflect whether a policy is considered a mandate _versus_ a recommendation. This addition was made to better reflect the types of individual policies being enacted at the state-level, particularly in relation to "StateAtHome" and "NEBusinessClose" codings. For "StayAtHome"

**_State updates_**  
_Full documentation is in-progress for March 30_
- **Maryland**: "StayAtHome" issued 20200330, enacted on 20200330.    
- **Oklahoma**: Updated "NEBusinessClose" to be coded as 0 for StateWide as this issuance is only applicable to counties with community spread.    
- **Oregon**: Recoded "NEBusinessClose" on 20200323 to "OtherBusinessClose" as the mandate delineates only certain business for closure and does not diretly require all non-essential businesses to close.    
- **Virginia**: "StayAtHome" issued 20200330, enacted 20200330.

### March 29, 2020 (5:16 am PST)  
**_File updates_**
- Added "DateExpiry" to capture the time, as applicable or provided, at which a given policy issuance is meant to expire in the absence of a deliberate extension, amendment, etc. Work is ongoing to capture this information for earlier policy issuances.  
- Added "LastUpdatedNotes" to provide additional detail, as helpful, to data updates.  

**_State updates_**  
_Full documentation is in-progress for March 29_  
- Policies for which enactment occurred at 11:59 pm on date x are now being coded as the following day (datex+1). Work is ongoing to ensure this proper data capture; "NEBusinessClose" and "StayAtHome" are the current priorities for this. Where changes have occurred already, they are documented under "LastUpdatedNotes" for 20200329.

### March 27, 2020 (5:49 am PST)  
**_File updates_**
- Merged "location_id" and "StateFIPS" into master data file to enable easier use.  
- Removed date stamp from the most up-to-date file to reduce potential issues with pulling datasets from the repo; archived datasets include the date stamp of their upload.

**_State updates_**  
- **Colorado**: "NEBusinessCLose" and "StayAtHome" issued on 20200325, goes into effect on 20200326.    
- **Georgia**: Added "PolicySource" for limited "StayAtHome".    
- **Hawaii**: "SchoolClose" extension issued 20200324.    
- **Indiana**: "RestaurantRestrict" issued on 20200323, goes into effect on 20200324; further issuance of banning in-person dining in restaurants.    
- **Massachusetts**: "SchoolClose" extension issued 20200325.    
- **Nevada**: "GathRestrict10" issued on 20200324; involves more stringent restrictions than the 20200319 issuance.    
- **Pennsylvania**: "StayAtHome" are separated into individual entries, wherein 20200323 was the initial issuance for Allegheny County, Bucks County, Chester County, Delaware County, Monroe County, Montgomery County, and Philadelphia County; 20200324 was for Erie County; and 20200325 was for Lehigh and Northampton Counties.    
- **South Carolina**: "SchoolClose" extension issued 20200326.    
- **Utah**: "SchoolClose" extension for public schools issued 20200323.


### March 26, 2020 (8:35 am PST)  
**_File updates_**
- Added variable "DateEnded" to capture time of policy discontinuation; this is meant to reflect a deliberate action to end the policy rather than its expiration per executive order.

**_State updates_**  
- **Arkansas**: "OtherBusinessClose" issued on 20200323.    
- **Connecticut**: "SchoolClose" formally extended 20200324.    
- **Delaware**: "SchoolClose" issued on 20200323.  
- **District of Columbia**: "NEBusinessClose" issued on 20200324, goes into effect on 20200325; "GathRestrict10" issued on 20200324.  
- **Georgia**: "StayAtHome" for specified populations issued on 20200323, goes into effect on 20200324; coded as local only.  
- **Idaho**: "StayAtHome" and "NEBusinessClose" issued on 20200325; also codes to "RestaurantRestrict", "GatherRestrictAny", and "OtherBusinessClose".  
- **Iowa**: "OtherBusinessClose" issued on 20200322.  
- **Kansas**: "GathRestrict10" issued on 20200324, goes into effect on 20200325.  
- **Kentucky**: "NEBusinessClose" issued on 20200324 for all "all non-life sustaining businesses; previously coded "NEBusinessClose" was for all non-essential *retail* and thus was revised to "OtherBusinessClose" issued on 20200322, goes into effect 20200323.  
- **Maine**: "OtherBusinessClose" issued on 20200324, goes into effect on 20200325.  
- **Michigan**: "OtherBusinessClose" issued on 20200321, goes into effect on 20200322.  
- **Minnesota**: "StayAtHome" issued on 20200325, goes into effect on 20200327.  
- **Mississippi**: "GatherRestrictAny", "GatherRestrict10", and "RestaurantRestrict" issued on 20200324.  
- **Montana**: "GatherRestrict10" issued on 20200324.  
- **Nebraska**: "RestaurantRestrict" issuance on 20200319 updated to reflect that restaurants are allowed to have onsite dining if they restrict serving no more than 10 patrons at a time.  
- **Nebraska**: "SchoolClose" for local schools has updated "PolicyScore" from the Department of Education.  
- **Oklahoma**: "NEBusinessClose" issued on 20200324, goes into effect 20200325; also applies to "RestaurantRestrict" and "OtherBusinessClose". "StayAtHome" is limited to adults over 65 and individuals with underlying medical conditions; coded as local only. "GatherRestrict10" and thus "GatherRestrictAny" are included in the non-essential business closure issuance.    
- **Tennessee**: "SchoolClose" involves governor urging public school closures but not mandating them.  
- **Utah**: "GatherRestrict10" notes under "PolicyCodingNotes" indicate that the order was amended to remove potential criminal association for gathering restriction.  
- **Vermont**: "StayAtHome" issued on 20200324; "NEBusinessClose" issued on 20200324, goes in effect on 20200325.
- **Wisconsin**: "OtherBusinessClose" issued on 20200320.  
- **Wyoming**: "OtherBusinessClose" issued on 20200324, goes in effect on 20200325.
