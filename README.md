# CBT385
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 385 IS FROM THE HARTFORD INSURANCE GROUP AND CONTAINS     *   FILE 385
//*           THE FOLLOWING PROGRAM DESIGNED TO COMPARE TWO         *   FILE 385
//*           COPIES OF LPALIB AND REPORT ON DIFFERENCES IN         *   FILE 385
//*           THEM.  IT ALSO COMPARES ONE OF THE LPALIB COPIES      *   FILE 385
//*           TO LINKLIB TO REPORT ON DUPLICATE MEMBERS.  JCL IS    *   FILE 385
//*           AS FOLLOWS :                                          *   FILE 385
//*                                                                 *   FILE 385
//*            OLDLPA   - POINTS TO THE 'OLD' COPY                  *   FILE 385
//*                       OF LPALIB                                 *   FILE 385
//*            NEWLPA   - POINTS TO THE 'NEW' COPY                  *   FILE 385
//*                       OF LPALIB                                 *   FILE 385
//*            LINKLIB  - OPTIONAL, POINTS TO A                     *   FILE 385
//*                       COPY OF LINKLIB THAT IS                   *   FILE 385
//*                       COMPARED TO THE NEWLPA                    *   FILE 385
//*                       DD.  IF NOT DESIRED,                      *   FILE 385
//*                       DUMMY THIS DD STATEMENT.                  *   FILE 385
//*            REPORT1  - MEMBERS IN OLDLPA THAT                    *   FILE 385
//*                       ARE NOT IN THE                            *   FILE 385
//*                       NEWLPA                                    *   FILE 385
//*            REPORT2  - MEMBERS IN NEWLPA THAT                    *   FILE 385
//*                       ARE NOT IN THE OLDLPA                     *   FILE 385
//*            REPORT3  - DUPLICATE MEMBERS                         *   FILE 385
//*                       BETWEEN LPALIB AND                        *   FILE 385
//*                       LINKLIB                                   *   FILE 385
//*            REPORT4  - CHANGES IN MODULE LENGTH                  *   FILE 385
//*                       OF MEMBERS THAT OCCUR IN                  *   FILE 385
//*                       BOTH OLDLPA AND NEWLPA.                   *   FILE 385
//*                                                                 *   FILE 385
//*            ALL REPORTS GIVE MODULE SIZE, INDICATE               *   FILE 385
//*            ALIAS ENTRIES, (NO SIZE GIVEN FOR ALIASES,           *   FILE 385
//*            AND REPORT ON TOTAL DIFFERENCES.  REPORT 4           *   FILE 385
//*            WILL SHOW THE DIFFERENCE IN SIZE OF TWO              *   FILE 385
//*            COPIES OF THE SAME MODULE, AND WILL REPORT           *   FILE 385
//*            ON THE TOTAL SIZE DIFFERENCE OF THE MODULES          *   FILE 385
//*            LISTED.                                              *   FILE 385
//*                                                                 *   FILE 385
```
