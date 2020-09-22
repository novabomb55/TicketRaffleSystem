Brief description of the intended change

ticketraffleSystem.js
- Changed Entry System to accruately use Sub multiplier (Currently purchasing 101 tickets on a 100 max entries 2x sub bonus results in the user being unable to purchase the 99 more)
- Added !max. A command that enters a person as much as physically possible. Taking the math out of the viewers hands
- Changed !ticket to accept no [amount]. Instead defaults to 1 ticket purchase request

New var values: trueSubsMaxEntries + trueRegMaxEntries + ownedTickets (Last one could be deleted by simply using getTickets(sender) over and over + Only used in !max)