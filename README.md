~~~~~~~~~~~~~~~~

//***FILE 066 is from Alan Field and contains several of his        *   FILE 066
//*           utilities.                                            *   FILE 066
//*                                                                 *   FILE 066
//*              email:    alan_c_field@bluecrossmn.com             *   FILE 066
//*                                                                 *   FILE 066
//*     This PDS contains the following members:                    *   FILE 066
//*                                                                 *   FILE 066
//*     Note:    ASM and MACROS members replaced with later         *   FILE 066
//*              versions.  (SBG - 2012/02/17)                      *   FILE 066
//*                                                                 *   FILE 066
//*     Note:    Member #PDSLOAD now contains an object deck        *   FILE 066
//*              for the PDSLOAD program, right in this file,       *   FILE 066
//*              together with appropriate linkedit JCL.            *   FILE 066
//*                                                                 *   FILE 066
//*     $$DOC    - This member.                                     *   FILE 066
//*                                                                 *   FILE 066
//*     ASM      - Assembler language source for some useful        *   FILE 066
//*                utilities.                                       *   FILE 066
//*                                                                 *   FILE 066
//*                ASCBSLOT - List page dataset slot usage by       *   FILE 066
//*                           job.                                  *   FILE 066
//*                CHPID    - Convert PCHID to CHPID.               *   FILE 066
//*                CPCMD    - Issue VM commands from TSO.           *   FILE 066
//*                CPFSET   - Demonstrate setting Command           *   FILE 066
//*                           prefixes.                             *   FILE 066
//*                CSALST   - List info about CSA usage.            *   FILE 066
//*                DISASM3B - SVC table.                            *   FILE 066
//*                DSSLVL   - Display level of DFDSS.               *   FILE 066
//*                DXCFSTR  - Display CF structure info.            *   FILE 066
//*                IEECMDPF - Set cmd prefix equal to sysname.      *   FILE 066
//*                INFO     - Search by keyword for info.           *   FILE 066
//*                IOCDSLST - List IOCDS info.                      *   FILE 066
//*                IPLSTAT  - IPL strp timing.                      *   FILE 066
//*                JULSUB   - Julian date manipulation              *   FILE 066
//*                           subroutine.                           *   FILE 066
//*                LASTCLPA - Date/time of last CLPA.               *   FILE 066
//*                           (Fixed for z/OS 2.2 and later)        *   FILE 066
//*                LASTXCF  - Date/time of last SYSPLEX start.      *   FILE 066
//*                LELVL    - Lang. Env level and options.          *   FILE 066
//*                LNKLST   - List LNKLST datasets.                 *   FILE 066
//*                LPARCAP  - Display LPAR capacity.                *   FILE 066
//*                MONJOBS  - STC to detect looping jobs and        *   FILE 066
//*                           write WTO.                            *   FILE 066
//*                MONJOBSS - Subroutine for MONJOBS.               *   FILE 066
//*                RACFDS   - Display RACF dataset names.           *   FILE 066
//*                RETCODE  - Set return codes based on various     *   FILE 066
//*                           criteria.                             *   FILE 066
//*                SHOWLPAR - Display LPAR information.             *   FILE 066
//*                SMFDS    - Display SMF dataset information.      *   FILE 066
//*                SMFSRCH  - Search SMF records for dataset        *   FILE 066
//*                           activity.                             *   FILE 066
//*                SVCTAB   - Display SVC table.                    *   FILE 066
//*                TODCN    - Convert TOD clock values.             *   FILE 066
//*                                                                 *   FILE 066
//*     CLIST    - CLISTS to demonstrate the use of some of the     *   FILE 066
//*                utilities included in this file.                 *   FILE 066
//*                                                                 *   FILE 066
//*     CNTL     - JCL to run some of the utilities.                *   FILE 066
//*                                                                 *   FILE 066
//*     INFOSYS  - Sample members for the INFO command.             *   FILE 066
//*                                                                 *   FILE 066
//*     MACROS   - Macros necessary to assemble source in           *   FILE 066
//*                member ASM.                                      *   FILE 066
//*                                                                 *   FILE 066
//*     PANELS   - ISPF panels.                                     *   FILE 066
//*                                                                 *   FILE 066
//*     PLI      - A PL/I utility to sort IEHLIST LISTVTOC          *   FILE 066
//*                output into address order.                       *   FILE 066
//*                                                                 *   FILE 066
//*     USERMODS - System usermods (SMP/E format):                  *   FILE 066
//*                                                                 *   FILE 066
//*                LM00026 - TSO TEST command mod.                  *   FILE 066
//*                LM00031 - Mod to message IEE163I to display      *   FILE 066
//*                          the following:                         *   FILE 066
//*                     IEE163I MODE= RD-HNR423/C25D-SP7.0.4        *   FILE 066
//*                                                                 *   FILE 066
~~~~~~~~~~~~~~~~

