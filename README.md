Odoo-Talend-Component
========================

Input and Output Component for Talend Open Studio (Dataintegration)

Recently we were looking for Talend Odoo (formerly known as OpenERP) components but soon discovered that there aren't any.

As a result we developed two new community components:

tOpenERPInput for reading objects
tOpenERPOutput for object creation, updates and object deletion

An example Talend Job (Version 5.3) is included. Just create a new Talend-Job and use File/Import.

Further information and an instruction about the use of the properties of the components can be found at our blog:
http://datenpol.at/unternehmen/blog/datenpol-creates-talend-component-for-openerp/

Thanks to the creators of the OpenERP Java API which we used as core library to communicate with Odoo
http://sourceforge.net/projects/openerpjavaapi/


Note 23rd April 2015
--------------------

We didn't test the component with reason versions of talend. There seem some problems with these versions or maybe with Odoo 8.
As soon as there is time - right now are in the middle of projects - we will fix the issues and add some new features. we would be happy about everyone who could fork the project here on Github and fix the problems in the meanwhile.
