About:
--------

The JDBC Account Tracking package contains policies and global configuration settings for identity tracking. The add on package enables the monitoring capabilities on the user account status.

What's New
-----------------
2.3.0
- New Policy sub-ctp-UpdateAccountsForMerge has been added (Bug #1015770).

2.2.0
- weightage for the policies are updated.

2.1.0
- Modifying itp-write accounts so as to accommodate the fanout driver associations in account tracking.
- Dirxml-Accounts attribute is not getting removed during Revoke entitlement operation, with delete option (Bug #800483)
- Dirxml-Accounts attribute showing wrong value, when user get Disabled/Enabled at IDV (Bug #802813)
- Also, completely re-written to cover all the scenarios

2.0.1
- On Account Entitlement Revoke, fix on policy to remove DirXML Accounts attribute
- On Account Tracking Identifier value change, fix on policies to reflect value change in DirXML Accounts attribute

2.0.0
- Initial JDBC Packages release for 4.x customers onwards