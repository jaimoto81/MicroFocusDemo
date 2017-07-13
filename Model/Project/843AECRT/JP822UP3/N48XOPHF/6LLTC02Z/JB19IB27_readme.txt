About
---------

Contains common policies used in password synchronization. This common package requires a driver-specific counter package to be installed additionally to complete the configuration and for password synchronization to function.


What's New
2.0.0
Contains a policy change as mentioned in 835251 comment#25.
If the modification of nspmDistributionPassword is due to a failed sync, then while converting this modify event to modify-password event, there will be a new attribute failed-sync added in the modify-password event.

-----------------

1.0.3
- Internal Bug Fixes(#755434)

1.0.2
-Contains Fix for Bug # 703888
https://bugzilla.novell.com/show_bug.cgi?id=703888

1.0.1
- Contains Fix for Bug # 694912 
https://bugzilla.novell.com/show_bug.cgi?id=694912

1.0.0
- Novell Identity Manager 4.0 ISO release