from random import randint
import Items
#mob class template
class mob():
    def __init__(self, name, HP, dmg):
        self.name=name
        self.HP=HP
        self.dmg=dmg
        
    def alive(self):
        return self.HP > 0
    if not alive(self):
        print "\nDefeated"
        
#---------------------------------------------
#Player
class Player(mob):
    def __init__(self):
        super().__init__(name="Player",
                         HP=50)
#---------------------------------------------
#Enemy
class Politician(mob):
    def __init__(self):
        super().__init__(name="Politician",
                         HP=20,
                         dmg=randint(3,6))

class Thug(mob):
    def __init__(self):
        super().__init__(name="Thug",
                         HP=25,
                         dmg=randint(4,8))

class Hippie(mob):
    def __init__(self):
        super().__init__(name="Hippie",
                         HP=10,
                         dmg=randint(2,4))

class Cultist(mob):
    def __init__(self):
        super().__init__(name="Cultist",
                         HP=15,
                         dmg=randint(2,4))

class Mad_Nerd(mob):
    def __init__(self):
        super().__init__(name="Mad Nerd",
                         HP=10,
                         dmg=randint(1,2))
