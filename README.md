# What-day-of-the-week-

# create an array

greeting = [
	"Приветствуем, Вас у нас в гостях!.. Оу, сегодня у нас",
	"О какие люди! А вы знаете какой сегодня день?! Правильно! Сегодня -",
	"Сегодня"
]

# find the day of the week

time = Time.now
week_day = time.wday

# we define an array with the names of the days of the week

day = [
	"Понедельник",
	"Вторник",
	"Среда",
	"Четверг",
	"Пятница",
	"Суббота",
	"Воскресенье"
]

# output according to the array day of the week

print "#{greeting.sample} #{day[week_day - 1]}."
