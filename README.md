# CBT827
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 827 is from John C. Miller and contains dialogs to help   *   FILE 827
//*           administer RACF.                                      *   FILE 827
//*                                                                 *   FILE 827
//*           email: "John C. Miller" <john@jmit.com>               *   FILE 827
//*                                                                 *   FILE 827
//*     (The older version of this package has been moved here      *   FILE 827
//*     from File 609.  That version is in members RFLDOLD and      *   FILE 827
//*     $RFLDOLD.)                                                  *   FILE 827
//*                                                                 *   FILE 827
//*     RLP is an updated version of my RACF profile utility.       *   FILE 827
//*     I added some requested features, including:                 *   FILE 827
//*                                                                 *   FILE 827
//*     - A simple user options panel;                              *   FILE 827
//*     - The option of confirm/noconfirm for profile deletes;      *   FILE 827
//*     - The option to have the dialog display the RACF            *   FILE 827
//*       commands being issued "under the covers"  for each        *   FILE 827
//*       operation done. This is a good learning tool for those    *   FILE 827
//*       new to RACF;                                              *   FILE 827
//*     - For DATASET class, the ability to enter a fully           *   FILE 827
//*       qualified dataset name in the "Filter" field, in which    *   FILE 827
//*       case the list of profiles is narrowed down to the one     *   FILE 827
//*       profile that covers the dataset entered.  This is         *   FILE 827
//*       useful when one needs to grant permission to a            *   FILE 827
//*       dataset, but is unsure of which profile to tweak.         *   FILE 827
//*     - Fixed assorted bugs and cleaned things up a bit,          *   FILE 827
//*       improving support for some RACF classes.                  *   FILE 827
//*                                                                 *   FILE 827
//*     ----------- RLP - RACF Lisf Profiles V2.1 --------------    *   FILE 827
//*     Thus ISPF dialog can be used to supplement the IBM          *   FILE 827
//*     provided dialogs for RACF administration.  Let me know      *   FILE 827
//*     if you find this facility useful by dropping me an email    *   FILE 827
//*     at software@jmit.com.  Thanks - John Miller                 *   FILE 827
//*                                                                 *   FILE 827
//*     -------------------- Install ---------------------------    *   FILE 827
//*     Installation is simple:                                     *   FILE 827
//*                                                                 *   FILE 827
//*     1) FTP the XMIT format file from your PC to an MVS or       *   FILE 827
//*        z/OS system.  Be sure that the file you FTP into is      *   FILE 827
//*        RECFM=FB, LRECL=80.  The FTP must be done in binary      *   FILE 827
//*        mode.                                                    *   FILE 827
//*                                                                 *   FILE 827
//*     2) From an ISPF command prompt, enter: TSO RECEIVE          *   FILE 827
//*        INDA('xmitfile') The resulting file contains             *   FILE 827
//*        everything (almost) needed for RLP.  Rename this file    *   FILE 827
//*        to whatever meets your system standards.  SYS2.RLP       *   FILE 827
//*        might be a reasonable name.                              *   FILE 827
//*                                                                 *   FILE 827
//*     3) Edit the #RLP member, and enter the name of your         *   FILE 827
//*        dataset from step 2.  (e.g. SYS2.RLP).                   *   FILE 827
//*                                                                 *   FILE 827
//*     4) Copy the modified #RLP member to one of your system      *   FILE 827
//*        clist libraries, and name it something convenient,       *   FILE 827
//*        like 'RLP'.                                              *   FILE 827
//*                                                                 *   FILE 827
//*     Now you should be able to invoke the dialog from within     *   FILE 827
//*     ISPF by typing on any Command ===> TSO RLP                  *   FILE 827
//*                                                                 *   FILE 827
//*     ------------------- Change Log -------------------------    *   FILE 827
//*     Version 2.1                                                 *   FILE 827
//*     - This version mostly has some cleanup done in the execs    *   FILE 827
//*       and panels and some bugs fixed.  Other bugs no doubt      *   FILE 827
//*       remain.                                                   *   FILE 827
//*                                                                 *   FILE 827
//*     - Added an Options panel.  For now this panel lets you      *   FILE 827
//*       turn on/off confirmation of delete operations, and        *   FILE 827
//*       lets you turn on/off an option that lists the actual      *   FILE 827
//*       RACF command being done under the covers.  This           *   FILE 827
//*       feature was requested as an educational aid by a          *   FILE 827
//*       sysprog who was learning RACF.                            *   FILE 827
//*                                                                 *   FILE 827
//*     - See the comments in member RLP for more details on        *   FILE 827
//*       some of the things changed or fixed.                      *   FILE 827
//*                                                                 *   FILE 827
//*                                                                 *   FILE 827
//*                                                                 *   FILE 827
//*                                                                 *   FILE 827
//*                                                                 *   FILE 827
//*                                                                 *   FILE 827
//*                                                                 *   FILE 827
//*                                                                 *   FILE 827
//*                                                                 *   FILE 827
```
