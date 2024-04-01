class Instrument:
    def get_instrument_type(self):
        return type(self).__name__

class Drum(Instrument): # бубон
    pass
    
class Timpani(Instrument): # барабан
    pass

class Trombone(Instrument): # тромбон
    pass

class Flute(Instrument): # флейта
    pass

class Organ(Instrument): # орган
    pass

class Harmonica(Instrument): # гармоніка
    pass

class Accordion(Instrument): # баян
    pass

class Piano(Instrument): # рояль
    pass
    
class Percussion(Drum, Timpani): # ударні інструменти
    def get_instrument_type(self):
        return 'Drum, Timpani'

class Wind(Trombone, Flute, Organ): # духові інструменти
    def get_instrument_type(self):
        return 'Trombone, Flute, Organ'

class Keyboard(Harmonica, Accordion, Piano): # клавішні інструменти
    def get_instrument_type(self):
        return 'Harmonica, Accordion, Piano'

# Приклад використання
percussion = Percussion()
print(percussion.get_instrument_type())

wind = Wind()
print(wind.get_instrument_type())

keyboard = Keyboard()
print(keyboard.get_instrument_type())
