Start with all 88-character strings: 958958
Then remove all passwords with no lowercase (698698), all passwords with no uppercase (698698), all passwords with no digit (858858) and all passwords with no special character (628628).

But then you removed some passwords twice. You must add back all passwords with:

no lowercase AND no uppercase: 438438
no lowercase AND no digit: 598598
no lowercase AND no special: 368368
no uppercase AND no digit: 598598
no uppercase AND no special: 368368
no digit AND no special: 528528
But then you added back a few passwords too many times. For instance, an all-digit password was remove three times in the first step, then put back three times in the second step, so it must be removed again:

only lowercase: 268268
only uppercase: 268268
only digits: 108108
only special: 338338
Grand total:  958−698−698−858−628+438+598+368+598+368+528−268−268−108−338=3025989069143040≈3.026×1015
