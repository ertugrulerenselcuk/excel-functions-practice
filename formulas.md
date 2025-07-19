=COUNTA(A:A)

Counts all non-empty cells in the Invoice column.

📷 Screenshot: screenshots/counta.png

=COUNTIF(H:H, "France")
Counts how many rows have Country = France.

📷 Screenshot: screenshots/countifFrance.png

=COUNTIF(D:D, ">10")
Counts how many rows have Quantity > 10.

📷 Screenshot: screenshots/countifGreaterThan10.png

=COUNTIFS(H:H, "France", D:D, ">10")
Counts rows where:

Country is France

Quantity is greater than 10

📷 Screenshot: screenshots/countifsFranceandQuantities.png

=TRIM("   blank   ")
Removes leading and trailing spaces.
Returns: blank

📷 Screenshot: screenshots/trim.png

=CONCATENATE("FRANK", "JOHN", "JESSIE")
Returns: FRANKJOHNJESSIE

📷 Screenshot: screenshots/concat.png

=LEFT(J19, 3)
=RIGHT(J20, 5)
=RIGHT(LEFT(J24, 11), 2)
Extracts specific portions of a string.

📷 Screenshots:

screenshots/LEFT.png

screenshots/left+right.png

=WEEKDAY(J27, 11)
Returns numeric value for weekday (e.g., 3 = Thursday).

📷 Screenshot: screenshots/weekday.png

=EXACT(I32, J32)
Returns TRUE only if both strings are exactly the same (case-sensitive).

📷 Screenshot: screenshots/excat.png

=I32=J32
Returns TRUE even if case is different, as long as content matches.

📷 Screenshot: screenshots/equal.png

=SUMIF(H:H, "France", D:D)
Sums all Quantity values where Country = France.

📷 Screenshots:

screenshots/sumif.png

screenshots/sumifResult.png

=SUMIFS(D:D, H:H, "France", F:F, ">5")
Sums quantities where:

Country is France

Price is greater than 5

📷 Screenshot: screenshots/sumifs.png
