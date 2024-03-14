# cayenne
Cayenne - the Config Processor

Command: CAYENNE [options] parmfile [>output]

Summary: Converts Opus-CBCS binary system data files into a human-readable
         control file.  This is an update utility. It is not useful to those
         installing Opus-CBCS for the first time.

         Command   | Details                          | Abbreviation
         ----------+----------------------------------+------------
Options: -VERBOSE  | Give more information            | -V
         -NOSYSTEM | Do not convert SYSTEMx.BBS files | -NOS
         -NOMENU   | Do not convert ???PRIV.BBS files | -NOM
         -NOEVENT  | Do not convert SCHED.BBS file    | -NOE
         -NOUSER   | Do not convert USER.BBS file     | -NOU

Output:  All output is sent to the video display unless you redirect it
         to some other device.  See your DOS reference manual for help
         on redirecting standard output.
