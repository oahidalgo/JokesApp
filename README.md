A Asp.NET CORE MVC Project with Core Concepts.!

This application is a basic crud and search project that allows us to create, edit, list and delete any joke that we want. It allows us also to search any word we want through the database and obtain a joke that contains the searched word. It also implements the net Core library called Authorization, and it allows us to only do crud operations it the user is loged in.

Installation:
Download the latest Visual Studio Community Edition, and install it through recomended settings
Download the project
Run the following command on Package Manager Console: Update-Database
Run the project through Visual Studio

Documentation:

Create a login:
 -> Go to register tab
 -> Fill the email and passwords fields
 -> Confirm the emial by click the "Click here to confirm your account" link
 -> You will see a green message that says "Thank you for confirming your email"
Notes*: its importart to "confirm the email", that's the only way that your credentials are going to work with the app

You can only create, delete or update if you are loged in.
  * Create Test Case
    -> Go through the 'Jokes' tab
    -> Left Clic on Create New Link
    -> Enter A new Joke and it's answer
    -> Clic on create
  * Edit Test Case
    -> Go through the 'Jokes' tab
    -> Clic on Edit link in any Joke that is showed in the list
    -> Modify a Joke and it's answer
    -> Clic on Save
  * See the details test case
    -> Go through the 'Jokes' tab
    -> Clic on Details link in any Joke that is showed in the list
    -> See the answer
  * Delete Test Case 
    -> Go through the 'Jokes' tab
    -> Clic on Delete link in any Joke that is showed in the list
    -> Clic on Delete button
    -> Return to the list
  * Search Test Case
    -> Go through the 'Search' tab
    -> Enter the word you want to search
    -> If the word is contained in any joke, The joke or jokes are going to be listed.
