# CBT1007
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE1007 is from Reed Starnes and is a batch program from      *   FILE1007
//*           The University of North Carolina called DATOC.        *   FILE1007
//*           This is a batch program that can change fields in     *   FILE1007
//*           the VTOC of one, or many datasets.                    *   FILE1007
//*                                                                 *   FILE1007
//*           email:  Reed Starnes <rxstarn@gmail.com>              *   FILE1007
//*                                                                 *   FILE1007
//*     DATOC is a batch program for altering fields in dataset     *   FILE1007
//*     control blocks (DSCBs) of existing files on DASD            *   FILE1007
//*     volumes.  There are TSO tools such as PDS86 on File 182     *   FILE1007
//*     and ZAPDSCB on CBT File 566, and CDSCB on CBT File 300      *   FILE1007
//*     which can do the same thing, but this one is for batch.     *   FILE1007
//*                                                                 *   FILE1007
//*     The fields that can be changed are:                         *   FILE1007
//*                                                                 *   FILE1007
//*        SPACE:   Secondary allocation (quantity and units)       *   FILE1007
//*        DCB:     Dataset organization (DSORG)                    *   FILE1007
//*                 Record format (RECFM)                           *   FILE1007
//*                 Logical record length (LRECL)                   *   FILE1007
//*                 Block size (BLKSIZE)                            *   FILE1007
//*                 Key length (KEYLEN)                             *   FILE1007
//*                 Relative key position (RKP)                     *   FILE1007
//*                 Options code (OPTCD)                            *   FILE1007
//*                                                                 *   FILE1007
//*     The actual file data is not altered, only the F1 DSCB       *   FILE1007
//*     in the VTOC.  It is therefore the user's responsibility     *   FILE1007
//*     to ensure that the new values are compatible with each      *   FILE1007
//*     other and with the rest of the dataset attributes.          *   FILE1007
//*     Obviously, changing some of these fields could render       *   FILE1007
//*     the existing file unusable, and can be modified             *   FILE1007
//*     intelligently only if the data in the allocated area is     *   FILE1007
//*     to be completely replaced.                                  *   FILE1007
//*                                                                 *   FILE1007
//*     The program is completely controlled by DD cards.           *   FILE1007
//*     There is no PARM or any control cards.                      *   FILE1007
//*                                                                 *   FILE1007
```
