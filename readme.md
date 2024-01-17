Features :
    1. Set a new Alarm.
    2. Delete Alarm.
    3. Shut the Alarm.
    4. Real Time Clock.
    5. BackGround Changes colour on the basis of toggeling of Button.
    6. Real time Date

Approach:
    1.Clock
        -> Approach for clock is to use date.
        -> using asyrnchnous setInterval() the real time hours/minutes/seconds are updated
        -> Similarly Current Date is also achieved.
    
    2.Inputs
        -> [Hour, Minute, Second, AM/PM ] are the different Inputs that are needed from USER.
        -> Input type can also be used, but in this applicaiton Select Tag with Options are used.
        -> By default the current Time when the document is loaded is shown.
        -> On changing the units, its time for Alarm Set.

    3. Alarm 
        -> when the user sets alarm the Alarm List is shown in the RHS of the body.
        -> Unordered List is used for Lists.
        -> In the List Item user have the option of deleting current alarm.
        ->  When user deletes the current Alarm , it is deleted from the Alarm Array.
        -> Since it's deleted from Alarm Array the The Alarm will not ring.

    4. Shut Alarm
        -> When any of the alarm is ringing  there shows a option to shut the alarm
        -> The Shut Alarm button is displayed at the bottom of set alarm button.
        -> when the shut alarm is clicked ,using event listener the alarm is shutted.

    5. Background Change
        -> Using a toggle button it is possible to switch from light to dark mode. 


Link of Website : https://tirthajyotibol.github.io/skill_test1/