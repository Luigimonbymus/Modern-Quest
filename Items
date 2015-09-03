class item():
    def ___init___(self, name, desc, worth):
        self.name=name
        self.desc=desc
        self.worth=worth
    def _str_(self):
        return "{}\n=====\n{}\nWorth: {}\n".format(self.name, self.desc, self.worth)

class money(item):
    def __init__(self, csh):
        self.csh = csh
        super().__init__(name="Money",
                       desc="Dollar bills in cash.",
                       worth=self.csh)

class weapon(item):
    def __init__(self, name, desc, worth, dmg):
        self.dmg=dmg
        super().__init__(name,desc,value)
    def _str_(self):
        return "{}\n=====\n{}\nWorth: {}\nDmg: {}".format(self.name, self.desc, self.worth, self.dm)
class Bat(weapon):
    def __init__(self):
        super().__init__(name="Bat",
                       desc="Just an ordinary baseball bat.",
                       worth=3,
                       dmg=5)

class Stick(weapon):
    def __init__(self):
        super().__init__(name="Stick",
                       desc="A weak yet seemingly unbreakable branch from a tree.",
                       worth=1,
                       dmg=2)
class Chainsaw(weapon):
    def __init__(self):
        super().__init__(name="Chainsaw",
                       desc="This is overkill.",
                       worth=20,
                       dmg=15)
class GlassShrd(weapon):
    def __init__(self):
        super().__init__(name="Glass Shard",
                       desc="Broken sharp glass. It's a miracle your hand is not bleeding.",
                       worth=0,
                       dmg=4)
class Clackers(weapon):
    def __init__(self):
        super().__init__(name="Clackers",
                       desc="Balls of steel.",
                       worth=5,
                       dmg=5)
class Yoyo(weapon):
    def __init__(self):
        super().__init__(name="Yoyo",
                       desc="String plus plastic equals trick shots!",
                       worth=3,
                       dmg=5)

class FirstAid(item):
    def __init__(self):
        super().__init__(name="First-Aid",
                         desc="Heals your wounds.",
                         worth=3)
        self.heal=10
    def healing(self,HP):
        #Heals player


class SuperFA(FirstAid):
    def __init__(self):
        super().__init__(name="Super First-Aid",
                         desc="A clinic in a box.",
                         worth=5,
                         heal=20)

class HyperFA
    def __init__(self):
        super().__init__(name="Hyper First-Aid",
                         desc="Surgeon approved.",
                         worth=10,
                         heal=30)
