# provisionUser
Self Service Script to create new Entra User

This is a script to create new user with email address in your Entra. 
It can add the user to a Microsoft 365 mailing list (typically your all@ mail) but not Legacy Distribution Groups.

It will also create a TAP (temporary access pass) or allow you to create a TAP for an existing user.

# pre-reqs

The script is looking for an icon on the path /Library/Application Support/$companyName/display-icon.png or it will use the Azure icon from this repo.

# coming
adding an available license


# use

upload as a script in Jamf Pro and make availble as Self Service. Must be run as root or it won't be able to install SwiftDialog.pkg
