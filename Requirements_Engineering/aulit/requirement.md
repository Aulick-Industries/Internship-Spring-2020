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


* People adding new iteams, how much information does it need to make a new iteam, who can add new items, how to actually publish a new item, takes you back to the home screen, 

##### Finding People's #
* On The home page there will be a search

##### Inbox 
* The user will find their Inbox on the home page and it'll be for notifications. 

##### Acepting Personal Items
* Once a personal item is made click on the item in the **Inventory** on the home page
* When the item is selected click the **Lend To** button and type in the person's employee #.
* In order for the item to be marked as sent out in the Inventory the person wanting to use it has to sign in to their account and accept the item in their **Inbox** on the home page. 

##### Deleting Accounts
* Navigate to the home page and click **Delete Account**
* Type the employee's # in the **Which User** box
* Once finalized through the database that the account entered it an actual account, click the red **Are You Sure?** to wipe the account. 

##### Permissions
* When signed in Admins have overall access and regular users will have standard permissions.
* Regular Users - Making Personal Items, Viewing Past Records, Reporting Bugs. (searching inventory)
* Admin - Making Personal Items, Viewing Past Records, Reporting Bugs, Searching Inventory, Creating New Accounts, Getting the new hire the essentials for his desk, Creating New Items, Deleting      Accounts, 
* Unless given permission if a regular user is to attempt to do something without proper permission, they will be presented to sign in with an account with appropriate permission. 

##### Accessing the Website & Logining In
* The person trying the access the **Website** will be presented with a simple input for a **Username** & **Password** text boxes.
* Invalid Passowrds or Usernames will present you to **Try Again Message**.

##### Viewing Past Records
* On the top of the page there will be **Past Records** once clicked it'll redirect you.
* From that the page it will show you what you've had for a certian duration, or the whole history of the account from the database with you employee #. 

##### Navigating the Website
* Along the top of the page there will be **Main Links** and **Sub-Categories** under the main links also for you specfic destination.
* The Categories on the top for right now will be **Creating Items**, **Add User**, **Make New Personal Item**, **Search Inventory**, **Report Bug**, **Past Records**, **Delete Account**, **Inbox**

##### Reporting a Bug
* On the top of the home page will be **Report Bug**
* It will direct you and auto-enter you employee # while you enter your prefered email address **email**. Then it will ask you what you were tying to accomplish and what prevented you from doing that in a text box. 

##### Searching Inventory
* On the home page and click **Inventory**
* Once clicked it'll direct you to a search bar and type the specific **Categories**, **Unique Tag**, **Current Status**, or look through it through manually the **Standard Pictures**.

##### Creating New Items
* On the top of the home page you'll see **Creating Items** click it and you'll be redirected to make a new item. 
* Selecting the **Categories** for the item you are adding.
* The user will select **Standard Pictures** already provided or upload their own with the **Upload Icon**.
* In the process a **Unique Tag** will be provided automaticly for that specific item by it's category.
* The **Model Number** of the item will have to be entered in a text box. 
* The **Current Status** of the item will be open to checkout once it's finalized.

##### Category Tags
* Printer - **AOL-01**(randomly generated)
* Computer - **AOL-02**(randomly generated)
* Montior - **AOL-03**(randomly generated)
* Laptops - **AOL-04**(randomly generated)
* Ipad -  **AOL-05**(randomly generated)
* Unique Tags - **AOL-Unq**(randomly generated)


##### Admin Creating a Account 
* Will be required to enter their legal name under **Legal Name**.
* Select the **Current Position** at Aulicks
* Choose the **Location** of which building they'll be working at in a drop down.
* After that a username will be generated based on the employee's 4 digit number and it'll also be the employee's #.
* With a random generated password with the username. 
* After that click the green **Finalize** button and the information will be reviewed and made sure there's not overwrite information already in the database.

##### Getting the new hire the essentials for his desk
* On the Home page and clicking **Add User**.
* Click the **Search User** and type in the employee # and select them. 
* Then go to the **Inventory**, to now see what items are available and not with also searching specific tags for specific categories.

##### Making a personal item to lend
* Navigate to the top and look for **Make New Personal Item**
* Under **Categories** if it's really unique (or a standard item) click the **+** sign next to it and add one or select the appropriate category for that item.
* The **Unique Id** should pop up for that item in its text box. 
* You will be prompted to **Add Pictures** of your item if it's not already in the system. 
* There will be a **Unique Characteristics** type box for you to talk about your item. It could be as simple as saying the color, damages etc. 


#### Non-Functional

* The Web-App must be able to access the MySQL Database is less than one second.
* Usability - 
* Size - Need to know the size of potential database to later figure out the magnitude of things and how it will effect future additions. 
* Reliablility
* Security - once created the new user's account the password will be encycpted and sent over to the database to be safely kept. 
* Scalability - 
* Manageability -
* The sql database must have a distinct layout on how it will be quered in the future for future actions, and not to mess up people's information.
* Capacity - Making sure we have the right service to support all the employee's & item's
* Serviceability - 
* The website will have a standard color grade across the whole website. 


#### Domain

