def user_signup():
 user_n = input("Enter Username: ")
 if any(char.isdigit() for char in user_n) and len(user_n) >= 4 and any(char.isupper() for char in user_n): 
   print("Username Accepted")
 else:
   print("""-Username must contain a number 
-Must be longer than 4 characters
-Must have an uppercase letter
-Should not have spaces""")
   print("\n\n")
   user_signup()

user_signup()

print("\n\n")

def pass_signup():
  sign_up = input("Enter Password: ")
  if len(sign_up) >= 4 and any(char.isdigit() for char in sign_up) and any(char.isupper() for char in sign_up): #and not sign_up.find(' ')
    print("Password Accepted")
  else:
    print("Sorry, Password Not Strong Enough")
    print("\n\n")
    pass_signup()

  print("\n\n")
  pass_conf = input("Confirm Password: ")
  if pass_conf == sign_up:
    print("Password Confirmed")
  else:
    print("\n\n")
    pass_conf = input("Confirm Password: ")

pass_signup()

print("\n\n")

def sign_in():
  print("SIGN IN")

  user_n2 = input("Enter Your Username: ")
  sign_in = input("Enter Your Password: ")

  confirm_button = input("Confirm: Y/N: ")
  if confirm_button == "Y":
    if user_n2 == user_n and sign_in == pass_conf:
      print("Congratulations You are In!")
    else:
      print("Password or Username Wrong")
      user_n2 = input("Enter Your Username: ")
      sign_in = input("Enter Your Password: ")
      confirm_button = input("Confirm: Y/N: ")
  else:
    user_n2 = input("Enter Your Username: ")
    sign_in = input("Enter Your Password: ")
    confirm_button = input("Confirm: Y/N: ")

sign_in()
