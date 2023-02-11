# Hommewor_artur
class Vehicle:
    def __init__(self, max_speed, mileage):
        self.max_speed = max_speed
        self.mileage = mileage

modelX = Vehicle(240, 18)
print(modelX.max_speed, modelX.mileage)
class Car:
    pass
class Vehicle:

    def __init__(self, name, max_speed, mileage):
        self.name = name
        self.max_speed = max_speed
        self.mileage = mileage


class Bus(Vehicle):
    pass

school_volvo = Bus('School Volvo', 180, 12 )
print("model bus :", school_volvo.name, "max speed :", school_volvo.max_speed, "mileage :", school_volvo.mileage)
#4 slayd 12
class Vehicle:
    def init(self, name, max_speed, mileage):
        self.name = name
        self.max_speed = max_speed
        self.mileage = mileage


class Bus(Vehicle):
    set("Bus.seating_capacity(50)")
    pass


class Vehicle1:

    def init(self, name, max_speed, mileage, color, ):
        self.name = name
        self.max_speed = max_speed
        self.mileage = mileage
        self.color = color


pass


class Car1(Vehicle1):
    @classmethod
    def seating_capacity(cls):
        pass

car1 = Car1('White', 'School Volvo', 180, 12)
car2 = Car1('White', 'Audi Q5 ', 240, 18)

print('Color:', car1.color, 'Vehicle name:', car1.name, 'Speed:', car1.max_speed, 'Mileage:', car1.mileage, 'Color:',
      car2.color, 'Vehicle name:', car2.name,
      'Speed:', car2.max_speed,
      'Mileage:', car2.mileage)

pass


class Vehicle:
    def init(self, name, mileage, capacity):
        self.name = name
        self.mileage = mileage
        self.capacity = capacity

    def fare(self):
        return self.capacity * 110.0

class Bus3(Vehicle):
    pass

School_bus = Bus3("School Volvo", 12, 50)
print("Total Bus fare is:", School_bus.fare())

class Vehicle:
    def init(self, name, mileage, capacity, tires):
        self.name = name
        self.mileage = mileage
        self.capacity = capacity
        self.tires = tires


class Bus5(Vehicle):
    pass


School_bus = Bus5("School Volvo", 12, 50, "30")


print('name :', School_bus.name, 'tires:', School_bus.tires, 'mileage:', School_bus.mileage, 'tires:', School_bus.tires,
      "capacity:", School_bus.capacity, 'tires:', School_bus.tires)
