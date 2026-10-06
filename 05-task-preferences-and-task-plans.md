---
book_title: REALTYJUGGLER TASKS TUTORIAL
chapter_title: Task Preferences and Task Plans
chapter_number: 5
author: RealOrganized, Inc.
website: www.RealtyJuggler.com
---

# Chapter 5: Task Preferences and Task Plans

## Task Preferences

Several preferences relate to tasks and Automatic Tasks. Edit them by clicking the "Settings" icon in the Main section and then the "Preferences" icon. This is the Main:Settings:Preferences:Tasks section.

- The "Contact B-Day Reminders" setting controls whether Automatic Tasks remind you of your Contacts' B-Day and Anniversary dates.
- The "Close after 1, 7 and 30 days" option generates Automatic Tasks for post-close follow-up calls. Many agents like this. If you do not, change the drop-down to "Skip".
- The Housewarming gift reminder, when checked, reminds you to send a housewarming gift to your Buyer Closing client. Uncheck it if you do not want that.
- The "Retain Completed Tasks for:" option sets how long you want to keep completed tasks. Tasks are kept in full for that period. After that, only the Date and Task Description are retained. You can still view all completed tasks regardless of date using the "Service Report" tab.
- You can assign AutoTasks to individual team members by filling in the text fields on the Tasks tab with the first name of the team member assigned to those auto tasks. You can assign multiple categories by placing a comma between each category. This adds a category to the AutoTasks that matches the name you enter.
- You can also use color coding. The available colors are blue, green, purple, red, yellow, orange, turquoise, gray, boldblue, boldgreen and boldred. Type one of these colors into the text field and those AutoTasks are color coded for you.

> Image: A list of the supported color names, each on a block of its own color: blue, green, purple, red, yellow, orange, turquoise, gray (also written "or grey"), boldblue, boldgreen and boldred.

## Activity Plans vs Task Plans

RealtyJuggler has two tabs for each deal record: the Tasks tab and the Mail tab. Occasionally you need to apply a sequence of letters and a sequence of tasks together. For example, you may have a DRIP letter sequence and want a Task to notify you when that sequence is complete. Or you may want to send a letter and make a few phone calls as part of your follow-up plan for a prospect.

Other real estate CRM products, like Top Producer, offer Activity Plans, which combine tasks and letters. To do the same in RealtyJuggler, go to Main:Settings:Mail Forms. Create your DRIP letter sequence (see the users manual on Letters for instructions) and then click the "New DRIP Task" button. Fill in the information for your task and make sure it has the same DRIP Group name as your letters. When you apply that letter sequence, the tasks are added as well.

## Creating a Task Plan

> Image: The All Tasks icon, a black checkmark with the label "All Tasks" beneath it.

A task plan is a bundle of tasks you can apply all at once. To create your own Task Plan, follow the instructions below. Task plans are created in the Main:Settings:Task Plans section. YouTube Video Tutorial 19 shows the process visually.

For the first task in our plan, request that a DRIP Letter sequence be applied to this Prospect. Click the "New Task" button. This brings up information for the task. The Task Plan Group is the name of the bundle of tasks we are creating. Fill it in with "FSBO Prospect". For the Task, fill in "Start DRIP FSBO Letter Sequence". Leave everything else blank and click Done. We have created a single task in our task plan sequence.

> Image: Screenshot of the Task Plan Group field, a blue "Task Plan Group:" label with arrow and a text box containing "FSBO Project", with a drop-down below it suggesting "FSBO Project" and a Task Description field.

> Image: Screenshot of the Task Plan task form. Buttons are "Done", "Delete Task" and "Duplicate Task". Task Plan Group is "FSBO Project" and Task Description is "Apply Drip FSBO Letter Sequence". Fields include Categories, Due Date (0 days After Start Date), Repeat, Email Alarm and Notes.

Create a second task. This one reminds you to call your prospect once a week for 6 weeks:

1. Click the "New Task" button.
2. For the Task Plan Group, use the exact same task plan group name as before. This group is available by clicking the "Task Plan Group:" blue link to the left of the first text field and selecting the group from the yellow drop-down menu, or you can type the name.
3. For the Task Description, fill in "Call Prospect".
4. For the due date, fill in the number 7. This means the task is due 7 days from the date you apply the plan.
5. The "Repeat New Due Date Calculated from:" drop-down lets the new repeat due date adjust based on the last time you checked off the old task. Here that is what we want. For example, if we do not make our call for 2 weeks, the next call is 7 days after that late call. Had we selected "Old Due Date", the next due date would be calculated exactly 1 week after the first due date. We would use that option to call a prospect always on Mondays, for example.
6. Click "Done" to create this second task.

> Image: Screenshot of the second task form. Task Plan Group is "FSBO Project", Task Description is "Call Prospect", the "Add Phone Number(s) from" drop-down is set to "Client/Prospect" with red text "When this task is marked done, Last Contact date will be updated", Due Date is 7 days After Start Date, Repeat is None and Email Alarm is None.

The Tasks list should now look like this:

> Image: Screenshot of the Task Plans list. A "Show Task Plan Group:" drop-down is set to "All (2)" with a black checkmark beside it. Buttons are "Done" and "New Task". The table has columns Task Description, Due Date, Categories and Task Plan Group. Row 1: "Apply DRIP FSBO Letter Sequence", "0 Days After Start Date", group "FSBO Prospect". Row 2: "Call Prospect", "7 Days After Start Date", group "FSBO Prospect". Links at the bottom read Import, Export, Tasks Manual and Tutorial 19.

Tip: If several tasks have the same due date, you can specify their order using a numeric order as part of the task description. For example, if the descriptions below were used for three tasks due on the exact same Due Date:

- 01 – Pick Up Letter
- 02 – Take Letter To Buyer
- 03 – Take Signed Letter to Escrow Company

they would be ordered by the numeric order that is part of the Task Description.

## Creating an Advanced Task Plan

> Image: The Task Plans icon, a black checkmark with the label "Task Plans" beneath it.

For Closings, we need a task plan that uses due dates based on the Close Date and Contract Date. Go to Main:Settings:Task Plans and click the "New Task" button at the top of the screen.

For the first task, we send the final ratified contract by postal mail to our client right after all parties sign the contract. Click "New Task". For the "Task Plan Group:", enter "Sell Side Closing". For the "Task:", enter "Send By US Mail Signed Contract to Seller". From the "Start Date" drop-down menu, select "Acceptance Date". This makes the task due 0 days after the Acceptance date. Click Done.

> Image: Screenshot of the Task Plan form. Task Plan Group is "Sell Side Closing", Task Description is "Send By US Mail Signed Contract to Seller", Add Nothing is selected, Due Date is 0 days After Acceptance Date, and Email Alarm is None.

For the second task, we call our Seller 3 days before the Close Date to remind them of the closing date. Click "New Task". For the "Task Plan Group:", enter "Sell Side Closing". For the "Task:", enter "Contact Seller to Remind of Closing". Enter 3 for the Due Date and select "Before" from the "After" drop-down menu. Select "Close Date" from the "Start Date" drop-down menu. Click "Done".

> Image: Screenshot of the second advanced task form. Task Plan Group is "Sell Side Closing", Task Description is "Remind Seller of Closing", Due Date is 3 days Before Close Date, Repeat is None and Email Alarm is None.

We now have a plan with two tasks. Their due dates adjust automatically based on the Close Date and Acceptance Date. If one of these dates has not yet been set, the due date for the task is not displayed.

When you look at the Task Plans list, it can be confusing because all the Task Plans are listed at once. To filter the list to just the tasks for a single task plan, click the "Show Task Plan Group:" drop-down menu in the upper-right corner of the screen. You can also sort by any column by clicking the column heading.

> Image: Screenshot of the Task Plans list filtered to "Sell Side Closing (2)". The table has columns Task Description, Due Date, Categories and Task Plan Group. Row 1: "Send BY US Mail Signed Contract to seller", "0 Days After Start Date", "Sell Side Closing". Row 2: "Remind Seller of Closing", "3 Days After Close Date", "Sell Side Closing". A "Duplicate a Task Plan:" drop-down and links Import, Export, Tasks Manual and Tutorial 19 are below.

## Applying a Task Plan

Tasks are normally associated with specific Deal records (Prospect, Buyer, Listing or Closing) and Contact records. To assign the task plan we just created to a Prospect record:

1. Click the "Prospects" icon on the Main section of RealtyJuggler.
2. Click the "Tasks" tab on the left side of the screen.
3. Click the "Apply Task Plan" button at the top of the screen.

> Image: Screenshot of the Tasks tab toolbar with a yellow note icon and buttons "Done", "Apply Task Plan" and "New Task".

A screen appears where you select when you would like the plan to start. This is the "Start Date" used when you created your Task Plan template. Normally today's date is fine and you can leave it alone. Next, select the name of the task plan you want to use from the "Use:" drop-down menu.

> Image: Screenshot of the Apply Task Plan screen. A "Return" button is at the top. "Start Date:" shows the blue link "today". "Use:" is a drop-down reading "-- Task Plan Group --". A blue "Apply Task Plan" button is below.

Once you select the plan name, click the "Apply Task Plan" button. An alert asks whether it is OK to create xx tasks. Click OK.

You are then back on the "Tasks" tab and see the generated tasks with their due dates. As noted earlier, due dates for tasks can be fixed or floating (based on specific dates such as the Closing Date or Contract date).

## How to Rebuild a Task Plan

Changing your task plan on the Main:Settings:Task Plans screen has no effect on plans you have already applied. To rebuild any task plans already in use, go to the Tasks tab inside the deal record, delete the old tasks and apply your task plan again.

## Shifting a Late Task Plan Forward in Time

Sometimes you need to shift an applied task plan forward in time. Go to the deal or contact record and click the "Tasks" tab on the left. If a plan is late, RealtyJuggler shows a message: "One of your Tasks is behind schedule. Click here to shift forward the due date for all uncompleted tasks by xx days." Clicking the link shifts the uncompleted tasks forward by the appropriate number of days so you can start working on the first task due today.

> Image: Screenshot of a task list with columns Date, Task Description and Categories. Tasks include "Oct 30 Pay commission tax" (AutoTask Commission), "Oct 30 Send housewarming gift" (AutoTask Gift), "Oct 31 Post-close call (1 day)" (AutoTask PostClosing), "Nov 29 Buyer needs to Sign Purchase Agreement document", "Nov 29 Get key from seller", "Nov 29 Loan Status Pre-Qualified", "Nov 29 Put up sign", "Nov 29 Seller Needs to sign Purchase Agreement document", "Nov 29 Thank you letter" and "Earnest Money Deposit balance $5,000.00" (AutoTask Escrow). Below it, a yellow warning triangle precedes the red text "One of your Tasks is behind schedule by 1 days. Click here to shift forward the due date for all uncompleted tasks by 1 days."

---

[← Previous Chapter: Automatic Tasks for Listing Records](./04-automatic-tasks-for-listing-records.md) | [Next Chapter: Defaults, Activity Plans and Short Sales →](./06-defaults-activity-plans-and-short-sales.md)
