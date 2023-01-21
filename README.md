I manage a lot of diffirent Jamf enviroments and need make a enrollment url for automation or for endusers to enroll their devices.
I use the Enrollment Invitations in Jamf Pro.

Steps to create this.

1. Login to Jamf Pro
2. Go to Global setting (Gear icon top rigth)
3. Click SMTP server either configure a real SMTP or put in fake values to enable the Enrollment Invitations section in Jamf Pro.
<br>
<img
  src="SMTP%20Server%20Icon.png"
  alt="SMTP_Icon"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
  
  <img
  src="SMTP%20Server%20Settings.png"
  alt="SMTP_Settings"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
  <br>
4. Click Enrollment Invitations under Computers --> Enrollment Invitations
<br>
<img
  src="Enrollment%20Invitations%20Location.png"
  alt="EIL"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
  <br>
5. Click new --> type in a real email or fake one in my case I like to user app@none.com   <br>
6. Click next --> leave this section alone --> next   <br>
7. Pick the expiration date --> and check "Allow multiple uses" --> next   <br>
8. (Note if you used fake values it will say it failed which is fine) Click Done   <br>
9. Now under Enrollment Invitations click the one you just created.   <br>
<br>
<img
  src="Enrollment%20Invitations.png"
  alt="EILS"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
  <br>
10. Copy the Invitation ID and copy your Jamf Pro url like https://myorg.jamfcloud.com   <br>
11. Open this app Jamf Enrollment URL Generator.app and paste in the values.   <br>
<br>
<img
  src="P1.png"
  alt="P1"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
  <img
  src="P2.png"
  alt="P2"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
  <img
  src="P3.png"
  alt="P3"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
  <br>
12. At the end of the app it will copy the url to your macOS clipboard.   <br>
13. Done   <br>
