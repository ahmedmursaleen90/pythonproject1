# pythonproject1
this is my first internship project at Decode labs
my_task =[]

while True:
    print("\n...TO-DO_LIST...")
    print("1. Add Task")
    print("2. Display Task")
    print("3. Exit")

    choice = input("Enter your choice: ")

    if choice == "1":
        task = input("Enter a task: ")
        my_task.append(task)
        print("Task added..")
    
    elif choice == "2":
        print("\nYour Tasks:")
        for i,j in enumerate(my_task,1):
            print(i,j)

    elif choice == "3":
        print("Exit..")
        break
    
    else:
        print("Invalid input..")        


