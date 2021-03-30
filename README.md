# Python-Basic
class Phone:
    def add_color(self,color):
        self.color=color
        
    def add_cost(self,cost):
        self.cost=cost
        
    def show_color(self):
        return self.color
    
    def show_cost(self):
        return self.cost
    
    def make_call(self):
        print("Making Call")
    
    def play_game(self):
        print("Plaing Game")
        
   p1=Phone()
p1.add_color("Blue")
p1.make_call()
p2.show_cost()
p2=Phone()
p2.add_cost(100)
p2.play_game()
p2.make_call()
p2.show_cost()
