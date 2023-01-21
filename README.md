I manage a lot of diffirent Jamf enviroments and need make a enrollment url for automation or for endusers to enroll their devices.
I use the Enrollment Invitations in Jamf Pro.

Steps to create this.

1. Login to Jamf Pro
2. Go to Global setting (Gear icon top rigth)
3. Click SMTP server either configure a real SMTP or put in fake values to enable the Enrollment Invitations section in Jamf Pro.
4. ![SMTP Location]([http://url/to/img.png](https://github.com/kylejericson/Jamf-Enrollment-URL-Generator/blob/main/SMTP%20Server%20Icon.png))
5. ![SMTP Settings]([http://url/to/img.png](https://github.com/kylejericson/Jamf-Enrollment-URL-Generator/blob/main/SMTP%20Server%20Settings.png))
6. Click Enrollment Invitations under Computers --> Enrollment Invitations
7. Click new --> type in a real email or fake one in my case I like to user app@none.com
8. Click next --> leave this section alone --> next
9. Pick the expiration date --> and check "Allow multiple uses" --> next
10. (Note if you used fake values it will say it failed which is fine) Click Done
11. Now under Enrollment Invitations click the one you just created.
12. Copy the Invitation ID and copy your Jamf Pro url like https://myorg.jamfcloud.com
13. Open this app Jamf Enrollment URL Generator.app and paste in the values.
14. At the end of the app if will copy the url to your macOS clipboard.
15. Done
