# Git-Exercise10
class Memir():
    def __init__(self, volt):
        self.volt = volt
    def ToDigital(self):
        int=int(self.volt*204.6)
        binary= format(int,'b')
        return binary
    def SetDigitalValue(self):
        digValue = self.ToDigital(self)
        self.digValue = digValue
