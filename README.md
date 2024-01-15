# Odoo 17 Module



   ## Usage

1. Json file is a collection which is the task related to postman
2. There are other two modules: Please replace web module in your local as still I can just able to do as much customization as I tracedout.
3. The odoo17_test module is the custom module where I made some changes for web customization as well as CRM module related task.
4. Steps for many2many_tags multi select option:
   Please add following attribute to the field with many2many_tag widget. It wll allow to have a checkbox in Many2Many field.
```xml
<attribute name="multi_select">1</attribute>


