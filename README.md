#calendar program
import calendar
year=2024
print("Is leap year",calendar.isleap(year))

import calendar
leaps=calendar.leapdays(1925,2025)
print(leaps,ends='')

#finding leap year program
import calendar
leaps=calendar.leapdays(1925,2025)
print(leaps,ends='')

#date and time program
from datetime import date
d1=date(2025,5,9)
d2=date(2024,1,1)
difference=d1-d2
print("difference in dates:",difference.days)

#day abbrevation(lower case)
from datetime import date
today=date.today()
name=today.strftime("%A")
print("Today : ",name)

#printing first and last date of a month
import calendar
from datetime import date
year=2025
month=5
fday=date(year,month,1)
lday=date(year,month,calendar.monthrange(year,month)[1])
print("Firstday:",fday.strftime("%A,%Y-%M-%d"))
print("Lastday:",lday.strftime("%A,%Y-%M-%d"))

