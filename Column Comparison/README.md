## Between 2 columns - columns are ordered and need to do one-to-one mapping



## Between 2 columns - columns are not ordered and need to do matching

1. Column A has one set of values
2. Column C has second set of values
3. Apply formula on Column E2 - 

=VLOOKUP(A2, $C$2:$C$68, 1, FALSE)

where A2 = First start value in column 1
C2 = First start value in column 2
C68 = Last start value in column 2

4. Drag the E2 Cell till the end to apply formula on all cells.
