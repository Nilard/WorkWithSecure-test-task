
WorkWithSecure test task module
===============================

#1 Create field (text field: Last name) programatycally for users.

Field is created using the field_create_field() function in the hook_install() of workwithsecure.install

#2 Create admin page (custom webform) where admin can insert identical value last name for all users. Use BatchAPI.

Admin page is located at Administration - Configuration - Account settings - Update Last name (admin/config/people/accounts/last-name-update).

#3 Create custom multilanguage text field for custom webform (creates web-form with one text field).

To implement this task additional contributed modules are needed:
- Internationalization (https://www.drupal.org/project/i18n)
- Variable (https://www.drupal.org/project/variable)

Admin page is located at Administration - Configuration - System - Multilanguage text field (admin/config/system/workwithsecure-multilingual).

#4 Create admin page (custom webform) with 3 fields (secrectapi, data1, data2). When user click on Submit, it will send GET-query to example.com with arguments from fields.

Admin page is located at Administration - Configuration - System - WorkWithSecure GET-query (admin/config/system/workwithsecure-get-query).
