This repository demonstrates a common numeric overflow bug in COBOL and its solution.  The original COBOL program attempts to add two 5-digit numbers, resulting in a sum that exceeds the field's capacity. The solution shows how to handle potential overflows using larger data types or checking for overflow conditions before performing the addition.