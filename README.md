# Samsung S24 Ultra Debloat

[Debloat list](s24_debloat_list.txt). It removes a lot of useless software and improves your phone performance.

I like to use [ADB AppControl](https://adbappcontrol.com/) for this, but you can also use the ADB CLI directly.

## Recommended process

So, I did a backup of everything to be able to factory reset my phone, and here is the step-by-step guide:

1. Factory reset your phone
2. Do the initial setup only connecting to Wi-Fi and then skipping and rejecting everything
3. Login into your Samsung Account
4. Update your apps at the Samsung Store (and search and install apps that are grey and bugged in the apps menu)
5. Update your apps at PlayStore
6. Enable developer mode and use the debloat list

That's it.

## My results

I have about 1.5 to 2.5 GB more free RAM compared to before, and I've noticed a ridiculous roughly 45% improvement in battery life.

## FIX ME

- Smart View (Mirror Screen wirelessly) and Samsung Dex wireless
  - Suspect removed packages:
    ```
    com.samsung.android.allshare.service.mediashare
    com.samsung.android.mdx
    com.samsung.android.oneconnect
    ```

- Lockscreen widgets and editing
  - Suspect removed packages:
    ```
    com.samsung.android.app.aodservice
    com.samsung.android.app.cocktailbarservice  
    ```

## Improvements

I wanna get rid completely of Google spyware features and improve my experience while using my phone, so:

- Install [F-Droid](https://f-droid.org/) and using it install:
  - Aurora Store
- Install [ReVanced Manager](https://revanced.app/download) and using it patch:
  - [YouTube](https://www.apkmirror.com/apk/google-inc/youtube/youtube-19-16-39-release/youtube-19-16-39-android-apk-download/)
  - [Photos](https://www.apkmirror.com/uploads/?appcategory=photos)
- Replace `Gmail` per `Thunderbird Beta for Testers`

TODO:
- Calendar
- Maps
- Contacts
- Wallet
