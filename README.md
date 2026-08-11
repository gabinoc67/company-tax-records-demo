# Company Tax Records Demo

Demonstration portal for a tax preparer to collect monthly deposit and expense details from two sample companies and reconcile those records against bank statements.

## Demo logins

- ABC Construction LLC — username `abcconstruction`, password `ABCdemo2026!`
- Sunrise Cleaning Services LLC — username `sunrisecleaning`, password `SUNdemo2026!`
- Tax Preparer Administrator — username `taxadmin`, password `ADMINdemo2026!`

## Demo workflow

Company users can enter deposits and expenses for their own company. The administrator can switch companies, verify entries against bank statements, and close a reconciled month. Once a month is closed, company entry controls are locked. The administrator can reopen a month and the action is added to the demo audit history.

The demo saves records in browser `localStorage`, so records persist after page refresh on the same browser/device.

## Important

This is a front-end demonstration only. The usernames and passwords are intentionally visible in the source code and are **not secure authentication**. Do not use this demo for real taxpayer, banking, or personally identifiable information. A production deployment should use server-side authentication, password hashing, role-based authorization, a secured database, HTTPS, backups, audit logging, and appropriate privacy/security controls.
