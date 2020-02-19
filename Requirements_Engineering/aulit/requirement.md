# AULIT Requirements

2020 Aulick Industries
Spring 2020 Internship

Lead Development Intern: Felipe VanWinkle

#### Functional

* A User must be associated with a username.
* A User must be associated with a password.
* Having access to eg. (certian permissions) when signed in. 
* Different authorizaition accounts with different permissions. 
* The user has the ability to see past records of what they had for a certian duration. 
* When the users' account is made they are given a employee # and with that they can see what items they've had checked out.
* The user is able to see how long they've haved an item for with the employee #.
* The ability to create specific id tags for items.
* The user will have a search bar to see what types of tags are specific with what type of items.
* The ability to enter a personal item with a unique tag to lend it to people.
* Admins are able to make new users and or add company owned property.
* Admins are able to delete regular users' accounts. 

##### Finding People's Employee #
* On The home page there will be a search bar to find specific peoples' employee # by their name, with their email attached. 

##### Inbox 
* **Inbox** on the home page and it'll be for notifications from co-workers, delevelopers, or mass updates. 

##### Acepting Personal Items
* The recipient will accept the item in their inbox. 
* In the sql database will register it as a "lend" and track it in the database. 

##### Deleting Accounts
* On the home page **Delete Account**
* Entering the employee's number and select them.
* Once finalized through the database that the account entered it an actual account, clicking **Are You Sure?** to wipe the account to wipe the account in the database. 

##### Permissions**
* When signed in Admins have overall access and regular users will have standard permissions.
* Regular Users - Making Personal Items, Viewing Past Records, Reporting Bugs. Searching inventory
* Admin - Making Personal Items, Viewing Past Records, Reporting Bugs, Searching Inventory, Creating New Accounts, Getting the new hire the essentials for his desk, Creating New Items, Deleting      Accounts.
* Unless given permission if a regular user is to attempt to do something without proper permission, they will be presented to sign in with an account with appropriate permission. 

##### Accessing the Website & Logining In
* Trying to access the **Website** will be presented with a simple input for a **Username** & **Password** text boxes.
* Invalid passowrds and or usernames will present you to **Try Again Message**.

##### Viewing Past Records
* On the home page **Past Records** 
* Search the # and it will show all items resembling it. 
* It will show you what you've had for a certian duration, or the whole history of the account.

##### Navigating the Website
* Along the top of the page there will be **Main Links** and **Sub-Categories** under the main links for your specfic destination.
* The Categories on the top for right now will be **Creating Items**, **Add User**, **Make New Personal Item**, **Search Inventory**, **Report Bug**, **Past Records**, **Delete Account**, **Inbox**

##### Reporting a Bug
* **Report a Bug** on the top of the home page.
* Type your issue in the text box provided. 
* It will direct you and auto-enter you employee # while you enter your prefered email address for contact. 

##### Searching Inventory
* **Inventory** on the home page. 
* It'll display a search bar and type the specific **Categories**, **Unique Tag**, **Current Status**, or look through it manually with the **Standard Pictures**.

##### Creating Items
* Main link **Create New Item**. 
* Selecting the **Categories** for the item you are adding.
* **Standard Pictures** already provided for the item. 
* Depending on the category it will come up with a **Unique Tag**
* The **Model Number** of the item will have to be entered.
* The **Current Status** of the item will be open to checkout once it's finalized in the database to make sure the same item isn't already added.

##### Category Tags
* Printer - **AOL-01**(randomly generated)
* Computer - **AOL-02**(randomly generated)
* Montior - **AOL-03**(randomly generated)
* Laptops - **AOL-04**(randomly generated)
* Ipad -  **AOL-05**(randomly generated)
* Unique Tags - **AOL-Unq**(randomly generated)


##### Admin Creating a Account 
* Legal name will be required.
* The **Current Position** at Aulicks.
* The **Location** of which building they'll be working at.
* After that a username will be generated based on the employee's 4 digit number and it'll also be the employee's #.
* With a random generated password with the corresponding username. 
* After that click the **Finalize** button and the information will be reviewed and made sure there's no overwrited information already in the database for the new account. 

##### Getting the new hire the essentials for his desk
* **Add User** will be a main link
* Will be able to look up the user while adding items form the inventory to that specific user.


##### Making a personal item to lend
* Main link for **Make New Personal Item**
* When selecting categories if it's a unique item select **Unique**
* The **Unique Id** should be auto-generated in a text box.
* **Add Pictures** of your item if it's not already in the system. 
* There will be a text box for you to describe your item.

#### Non-Functional

* The Web-App must be able to access the MySQL Database is less than one second.
* Usability - The way of navigating and adding additions. 
* Size - Needs to know the size of potential database(s) to later figure out the magnitude of things and how it will effect future additions. 
* Reliablility - Need the sever to be up and not get overloaded with useless information and be down when needed maintaince is needed. 
* Security - once created the new users' account the password will be encycpted and sent over to the database to be safely kept. 
* Scalability - Having for example 13 databases and changing it to 7 databases to now hold the information. 
* Manageability - Being able to see what databases are preforming like how they are intended to do and fixing them. 
* The sql database must have a distinct layout on how it will be quered in the future for future actions, and not conflict other information.
* Capacity - Making sure we have the right service (tables to transfer) to support all the employee's & item's
* Serviceability - Having the ability to delete tables and or databases without leaving or deleting extra to later cause confusion.
* The website will have a standard color grade system across the  website. 


#### Domain

