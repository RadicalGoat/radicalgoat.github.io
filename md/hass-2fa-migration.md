# Family Announcement

Issued: **7th April 2026**

I would like to ensure anyone who is using Home Assistant to ensure **Two-Factor Authentication** (2FA) is enabled on your account.

I would like you to do this within the **next 48 hours**.

I will allow you to do this yourself, rather than enforce it within the next 48 hours - but after that **I will block access if not enabled**.

To enable 2FA follow the steps below.

I recommend doing this from **within 30 Downshire Park** with WiFi enabled to ensure the App can find the local instance of Home Assistant once you try to login again.

The steps are:

- **Open** the Home Assistant (HA) App on your phone
- Open the main menu by selecting the **menu** button on the top-right
- Select your **user account** from the bottom of the menu
- Select the **Security** tab from the bottom of the screen
- Under **Multi-Factor authentication modules** select **Enable**
- You will be prompted to add your Home Assistant account to the Authenticator App of your choice.  Do this using the **QR Code** provided and **remember** the latest **six digit code** for that account.
- Return to the Home Assistant App
- Enter the **six digit code**
- Select the **General** tab
- Select **Log out**
- Re-start the Home Assistant App on your Phone
- When it starts it will look for the local Home Assistant and prompt you to login - follow the prompts
- You should then be logged in OK
- Turn something on and off to ensure you still have control

Once this is working, you should test that remote access is still working.  To do this, turn off **just** the Wifi on your phone and wait for a minute or so.  The Home Assistant App should detect the loss of LAN traffic and automatically switch to the remote Home Assistant Gateway.  Then, again, turn something on and off to ensure it works OK.  You can then turn your WiFi back on and it should revery back to the local instance of Home Assistant.

Periodically, it will also ask you to re-verify your 2FA code (probably once a month).  Just re-enter the latest code from your Authenticator App.

Have fun...
