Start with all $8$-character strings: $95^8$

Then remove all passwords with no lowercase ($69^8$), all passwords with no uppercase ($69^8$), all passwords with no digit ($85^8$) and all passwords with no special character ($62^8$).

But then you removed some passwords twice. You must add back all passwords with:

 - no lowercase AND no uppercase: $43^8$
 - no lowercase AND no digit: $59^8$
 - no lowercase AND no special: $36^8$
 - no uppercase AND no digit: $59^8$
 - no uppercase AND no special: $36^8$
 - no digit AND no special: $52^8$

But then you added back a few passwords too many times. For instance, an all-digit password was remove three times in the first step, then put back three times in the second step, so it must be removed again:

 - only lowercase: $26^8$
 - only uppercase: $26^8$
 - only digits: $10^8$
 - only special: $33^8$

Grand total: $95^8 - 69^8 - 69^8 - 85^8 - 62^8 + 43^8 + 59^8 + 36^8 + 59^8 + 36^8 + 52^8 - 26^8 - 26^8 - 10^8 - 33^8 = 3025989069143040 \approx 3.026\times10^{15}$
