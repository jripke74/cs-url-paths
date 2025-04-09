# cs-url-paths

STEP 1
Change language codes
Sofia wants to help users navigate around the Khan Academy site by constructing URLs to different pages.

The site offers content in several languages, indicated in the URL by a language code like es or pt. Sofia often uses the Portuguese site at pt, but she wants her program to show the Spanish site by default.

Modify the first assignment statement to assign the value "es" to the variable language_code.
You’ll need to replace the value "pt" with the value "es". When the program accesses language_code to construct the url, it should contain the value "es".
Code editor
Code files

STEP 2
Ask for a subject
Instead of always pointing to the computing page, Sofia wants to let the user choose their subject. Subjects include math, science, computing, and humanities, where the names are in all lowercase letters.

Add a new input() prompt that asks the user to enter a lowercase subject name.
Modify the program to print the URL for the subject the user entered.
You’ll need to assign the result of the input() call to the variable subject. When the program accesses subject to construct the url, it should contain the value the user entered.

STEP 3
Edit the instructions
Sofia wants the final instructions to be more specific. Instead of printing Navigate to the page below!, she wants the output to include the subject name. For example, if the user enters the subject math, the program should print, Navigate to the math page below!

Modify the printed instructions to include the subject name before the word “page”.
You’ll need to construct a string expression that accesses the subject variable’s value. Think about what string should be concatenated before subject and what string should go after.
Code editor

