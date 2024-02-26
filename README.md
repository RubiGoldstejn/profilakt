class Maintenance:
    def __init__(self, device_name):
        self.device_name = device_name

    def schedule_maintenance(self, date):
        print(f"Профилактика для устройства {self.device_name} запланирована на {date}")

# Пример использования класса Maintenance
device1 = Maintenance("Компьютер")
device1.schedule_maintenance("10 сентября 2021")
