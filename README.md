avalaible_seats = 8
required_seats = int(input("Enter the seats required: "))
while avalaible_seats > 0:
    print(f"{required_seats} are booked.")
    avalaible_seats = avalaible_seats - required_seats
    print("Remaing seats are: ",avalaible_seats)
    if avalaible_seats == 0:
         print("All the seats the booked.")
   
print("Currently no seats are available.")
