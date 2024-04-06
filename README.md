import datetime

# Joriy vaqtni olish
joriy_vaqt = datetime.datetime.now()

# Soat obyekti yaratish
soat = datetime.time(joriy_vaqt.hour, joriy_vaqt.minute, joriy_vaqt.second)

print("22:15:", soat)
