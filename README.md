# Alfred Apple Reminder

Following input is used to add reminders:
- *rm* with title or title&URL 
    - The URL will be automatically recognized and added to Reminder notes
- *due day* and *time* are empty: due day will be set to today with 3 hours from now
- *time* is empty: Reminder will be addes as reminder without a due date
- if list is empty it uses default list e.g. *Inbox*
- accepted date format: `<day>.<months>` or `<day>.<months>.<year>` or tomorrow, next week or `<weekday>`
    - *weekday*: Reminder will be set to the next weekday
    - accepted time format: `<hours>` or `<hours>:<minutes>`

