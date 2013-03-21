---
#Alfred for Trello - Workflow
###Create cards in Trello via @alfredapp for Mac.


**[Download Alfred for Trello 1.0](https://dl.dropbox.com/s/y62gy8eqg2amvpi/index.html )**


---

<br>

##Setup

1. Use the keyword "**jello**" to authorise Alfred for Trello to access your Trello information.
2. Copy the **token** generated by Trello.com
3. Open the Afred for Trello Workflow and enter the token in /bin/bash script: **token=''**
4. Go to your Trello.com board that you wish to use and copy the **Board ID**. You can find the Board ID in the last part of the URL. For example: https://trello.com/board/yourname/**4f21cb176603c3453fwf4e8d**
5. Enter the Board ID in /bin/bash script: **boardid=''**
6. Withing the Alfred for Trello workflow double click the Hotkey and set "Option + Command + t" or your preferred hotkey.


###Optional
You can specifify a list within your Trello board. 
Simply open the /bin/bash script within the workflow and enter the name of the list. For example if your list name is inbox enter:  **listname='inbox'**.
If you leave it blank **listname=''** the first list within your board will be used as default list.


<br>

##Usage

* **trello card name; description**


	Example: trello **Do work!; seriously, do work**

	**Do work!** Will be the Card title 

	**seriously, do work** Will be the Card description

	---

*  Alternatively you can **select any text** and press "**Option + Command + t**" (or your custom hotkey) to create a card in Trello with the selected text.