##Configuring PuTTY for the AP Backend##
PuTTY need to be configured properly in order to ensure a stable and secure connection to the AP VPS.

---
**1.**  
![Open PuTTY screenshot](open-putty.png)
> Open PuTTY

---
**2.**  
![Enter host name screenshot](add-host-name.png)
> Type `airshippirates.ddns.net` into the **Host Name** box

---
**3.**  
![Disable bell screenshot](bell-off.png)
> Go to **Terminal > Bell** then set the bell style to **None**

---
**4.**  
![Configure cursor appearance screenshot](cursor-app.png)
> Go to **Window > Appearance** then set the **Cursor appearance** to **Underline** and enable **Cursor blinks**

---
**5.**  
![Configure window name screenshot](win-name.png)
> Go to **Window > Behavior** then set the **Window title** to `NAME @ AP` but replace _NAME_ with your name

---
**6.**  
![Set auto-login username screenshot](set-user.png)
> Go to **Connection > Data** then set the **Auto-login username** to your account's username on the AP VPS.

---
**7.**  
![Enable compression screenshot](enable-comp.png)
> Go to **Connection > SSH** then **Enable Compression**

---
**8.**  
![Save configuration appearance screenshot](save-conf.png)
> Go to **Session** then set the **Saved Sessions** text box to `NAME @ AP` but replace _NAME_ with your name then press **Save** to save your PuTTY Configuration
