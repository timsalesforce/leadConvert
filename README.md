# W-1418530

To repro:
1. Clone this repository
2. Deploy to an org
3. Create a New Lead (note that the Record Type with be Lead1)
4. Click the Convert button
5. On the modal after lead conversion, click the goto lead list button

You might observe the popup error here (sometimes it doesn't surface to the user).  If you don't, then open DevTools, turn on pause on uncaught errors, and do it again.  You will see the error.

