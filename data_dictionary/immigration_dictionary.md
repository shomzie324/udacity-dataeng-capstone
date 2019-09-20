# Immigration Data Dictionary

- dem_id - identfier for demographic data for a given city/state
- temp_id - identifier for temourature data entry
- airport_id - identifier for a given airport in the US
- year - 4 digit year
- I94MON - Numeric month
- I94CIT & I94RES - This format shows all the valid and invalid codes for processingvalue i94cntyl
- entry_city - This format shows all the valid and invalid codes for processing */
- arrival_date is the Arrival Date in the USA. It is a SAS date numeric field that a 
   permament format has not been applied.  Please apply whichever date format 
   works for you.
- arrival_mode - There are missing values as well as not reported (9) */
    value i94model
- state - There is lots of invalid codes in this variable and the list below 
   shows what we have found to be valid, everything else goes into 'other' */
    value i94addrl
- DEPDATE is the Departure Date from the USA. It is a SAS date numeric field that 
   a permament format has not been applied.  Please apply whichever date format 
   works for you. */
- age - Age of Respondent in Years */
- visa type - Visa codes collapsed into three categories:
   1 = Business
   2 = Pleasure
   3 = Student
- COUNT - Used for summary statistics */
- DTADFILE - Character Date Field - Date added to I-94 Files - CIC does not use */
- VISAPOST - Department of State where where Visa was issued - CIC does not use */
- OCCUPATION - Occupation that will be performed in U.S. - CIC does not use */
- ENTDEPA - Arrival Flag - admitted or paroled into the U.S. - CIC does not use */
- ENTDEPD - Departure Flag - Departed, lost I-94 or is deceased - CIC does not use */
- ENTDEPU - Update Flag - Either apprehended, overstayed, adjusted to perm residence - CIC does not use */
- MATFLAG - Match flag - Match of arrival and departure records */
- BIRTH_YEAR - 4 digit year of birth */
- DTADDTO - Character Date Field - Date to which admitted to U.S. (allowed to stay until) - CIC does not use */
- GENDER - Non-immigrant sex */
- INSNUM - INS number */
- AIRLINE - Airline used to arrive in U.S. */
- ADMISSION_NUM - Admission Number */
- FLTNO - Flight number of Airline used to arrive in U.S. */
- VISA_CLASS - Class of admission legally admitting the non-immigrant to temporarily stay in U.S. */
    run ;

