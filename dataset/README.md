Please contact `byshen@ucsd.edu` to acquire the data of Permission Checker which is used in the
study.


### Sample data

```
{   'UID': '2bd67515-5921-35bb-a109-9f13c41f9195',
    'allapps': [ ...

                {   'appName': 'AdGuard Content Blocker',
                       'granted': [   'android.permission.INTERNET',
                                      'android.permission.ACCESS_NETWORK_STATE',
                                      'android.permission.RECEIVE_BOOT_COMPLETED'],
                       'packageName': 'com.adguard.android.contentblocker',
                       'requested': [   'android.permission.INTERNET',
                                        'com.samsung.android.sbrowser.permission.CONTENTBLOCKER',
                                        'android.permission.ACCESS_NETWORK_STATE',
                                        'android.permission.RECEIVE_BOOT_COMPLETED']}]}

```

The `allapps` field contains the list of all apps installed on this user’s phone. 
For each app, the data contains the app’s `packageName`, `appName`, the list of granted permissions and the list of all requested permissions in the Android Manifest.
