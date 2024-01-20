WEEK 3 CLASS SOLUTION
class myStringClass:
    def __init__(self, myString):
    	self.myString = myString
    def getString(self):
    	print(str((self.myString)).upper())
c1 = myStringClass("hello")
c1.getString()
