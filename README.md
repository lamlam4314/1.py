    choice = input("Choose an option: ")
    
    if choice == '1':
        category = input("Category: ")
        amount = float(input("Amount: "))
        description = input("Description: ")
        date = input("Date (YYYY-MM-DD): ")
        add_expense(category, amount, description, date)
        print("Expense added!")
    
    elif choice == '2':
        expenses = view_expenses()
        for expense in expenses:
            print(expense)
    
    elif choice == '3':
        total = total_expenses()
        print(f"Total Expenses: {total}")
    
    elif choice == '4':
        print("Exiting...")
        break
    
    else:
        print("Invalid choice. Please try again.")
#### My Stats 📈
![Your GitHubStats](https://github-readme-stats.vercel.app/api?username=lamlam4314&show_icons=true&theme=tokyonight)
