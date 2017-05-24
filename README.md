# Query-ideas

When working within the same spreadsheet, the following works:
=QUERY('TabName'!A:F," SELECT * WHERE A <> '' ORDER BY A, C desc, D, E asc, B",1)

When working by importing into another spreadsheet, the following works:
=QUERY({IMPORTRANGE("Key","TabName!A:F")}, "SELECT *",1)
