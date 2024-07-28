# SHOWZOST ISPF Dialog

SHOWZOST is an ISPF dialog that displays the SHOWZOS sections in
a selectable ISPF table where each section is a table row.

This dialog is written in REXX and dynamically loads the required
ISPF panels, which are located within the REXX code.

The only **REQUIRED** customization is to change the name of the
APF authorized library where SHOWZOS is installed. Note that if
the library is not APF authorized then some of the SHOWZOS sections
will not be generated.

SHOWZOS can be found on the www.cbttape.org site in File 492.

Thank you to Roland Schiradin for developing SHOWZOS....
