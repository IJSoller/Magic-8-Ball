# Magic-8-Ball
import randomimport timeimport sys
phrases = ["It is certain", "It is decidedly so", "Without a doubt", "Yes definitely", "You may rely on it", "As I see it, yes", "Most likely", "Outlook good", "Yes", "Signs point to yes", "Reply hazy try again", "Ask again later", "Better not tell you now", "Cannot predict now", "Concentrate and ask again", "Concentrate and ask again", "Don't count on it", "My reply is no", "My sources say no", "Outlook not so good", "Very doubtful"]
print("Welcome!")
def userinput():  
  input("What would you like to know? :) ")  
  print("I'm thinking, I'm thinking! Don't rush me!")  
  time.sleep(3)
  print(random.choice(phrases))    
  time.sleep(1) 
  secondary_userinput()
def secondary_userinput():  
  q = input("Would you like to play again? ;)")  
    if q == "yes":    
      userinput()  
    else:    
      print("Thanks for playing!")    
      sys.exit(0)  

userinput()


