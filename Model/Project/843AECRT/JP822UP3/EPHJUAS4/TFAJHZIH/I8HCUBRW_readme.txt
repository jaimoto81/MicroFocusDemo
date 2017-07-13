About:
--------

The JDBC Entitlement package contains policies, global configuration settings and entitlements for identity provisioning. The entitlement policies performs the account and group provisioning roles on the connected application.

What's New
-----------------
2.4.0
- GroupEntitlementAddStmtImpl policy in ctp has been updated w.r.t internal bug 956256.

2.3.0
- fix for the group entitlement revoke & weightage has been updated for the policy

2.2.0
- Verifying the Group entitements in publisher channel,Publisher's events will get veto in case the Group entitlement is enabled.(Buzilla ID:795779)

2.1.0
- Adding the proper association value to the json response of the below rest end point (assignment query)
          /idvdata/entitlements/assignments/ms/{GUID}/ls/{LSIDENT} 

2.0.1
-  Remove association action added for account entitlement revoke
-  Policy added to prevent login disabled attribute update on edir during merge operation

2.0.0
- Initial JDBC Packages release for 4.x customers onwards
