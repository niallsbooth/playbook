# Plugin updates

Plugin updates are checked and committed automatically, but tested and deployed
by developers. When there's one for you to do, you'll get a ticket.

## Process

1. Check out the update branch that's specified in the ticket:
   `git checkout <branch>`
1. Install the updated plugins: `whippet plugins install`
1. Fire up the site and do some testing. Click around the site, check areas of
   functionality that are powered by particular plugins that were updated
   (eg BuddyPress, Eventbrite), try to get a good random sampling
1. If you find problems, fix them. If you can't, update the ticket with what you
   found and assign to someone who can. If you learn something about the site
   that is generally useful, update its readme
1. When you are happy that the site is working, merge the update branch and
   deploy it
1. Finally, add a comment on the ticket to say what testing you did, and what
   fixes you made, if any.