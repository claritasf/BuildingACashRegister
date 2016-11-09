This is a simple Java Script ecercise to create a cashRegister Machine, this excercise can be found in Module 8 ef JS course of CodeCademy

The program creates an Object called cashRegister to tell the total of a purchase, a method called scan takes some item parameter, and adds the cost of this item to the total and finally give you the total amount, when you call the method indicating the quantity.

Besides that, it keeps track of how much the last transaction was in a new property, lastTransactionAmount and can subtracts the last amount transacted from total.

Additonally the cash register can apply staff discount accordint to each Staff Member, creating a method called applyStaffDiscount in the cashRegister object which accepts a parameter employee. When this method is called, cashRegister should apply the staff member's discountPercent to total.