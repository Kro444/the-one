
def da_ta():
    while True:
       value = input("enter a value: ")
       if "." in value:
            print("the dara type is float.")
            print(float(value))
       elif value.isdigit():
            print("the data type is integers.")
            print(int(value))
       else:
            print("the data type is string.")
            restart = input("do you wanna to know another type ? ")
       if    restart.lower()[0] != "y" :
          break
    return value 
da_ta()
