import calendar
year=2024
print("Is leap year",calendar.isleap(year))

import calendar
leaps=calendar.leapdays(1925,2025)
print(leaps,ends='')

import calendar
leaps=calendar.leapdays(1925,2025)
print(leaps,ends='')


from datetime import date
d1=date(2025,5,9)
d2=date(2024,1,1)
difference=d1-d2
print("difference in dates:",difference.days)
