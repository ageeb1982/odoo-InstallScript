# [Odoo](https://www.odoo.com "Odoo's Homepage") Install Script

This file is based on an executable file that installs the Udo system on Ubuntu and Linux Mint
We relied on the file from a page
 Yenthe Van Ginneken (https://github.com/Yenthe666/InstallScript)
With some improvements

يعتمد هذا الملف على ملف تنفيذي يقوم بتثبيت  نظام اودوو على نظام التشغيل أوبنتو ولينكس مينت
  اعتمدنا على الملف من صفحة
 <br/> Yenthe Van Ginneken (https://github.com/Yenthe666/InstallScript)
مع بعض التحسينات<br/> 
 

## Installation procedure - اجراءات التثبيت

##### 1. Download the script:
##### 1. تحميل الملف التنفيذي:
```
sudo wget https://raw.githubusercontent.com/ageeb1982/odoo-InstallScript/master/odoo_install.sh
```
##### 2. Modify the parameters as you wish.
##### 2.يمكنك تعديل المتغيرات -بارميترات- حسب رغبتك
There are a few things you can configure:<br/>
هناك بعض الأشياء التي يمكنك تخصيصها :<br/>
```OE_USER``` will be the username for the system user.يمكنك تغيير اسم المستخدم  <br/>
```INSTALL_WKHTMLTOPDF``` <br/>
set to ```False``` if you do not want to install Wkhtmltopdf, if you want to install it you should set it to ```True```.<br/>
<br/>
اضبط على <br/>
```False``` <br/>
إذا كنت لا تريد تثبيت <br/>
Wkhtmltopdf <br/>
،  إذا كنت تريد تثبيته يجب عليك ضبطه على <br/>
```True``` .<br/>
#### -----------------------------------------
```OE_PORT```
is the port where Odoo should run on, for example 8069.<br/>
   <br/>هو المنفذ الذي يجب أن يعمل فيه 
Odoo <br/>
على سبيل المثال 8069. <br/>
#### -----------------------------------------
```OE_VERSION``` 
is the Odoo version to install, for example ```11.0``` for Odoo V11.<br/>
 <br/>هو إصدار
Odoo <br/>
لتثبيته ، على سبيل المثال "11.0" لـ <br/>
Odoo V11. <br/>
#### -----------------------------------------

```IS_ENTERPRISE```
will install the Enterprise version on top of ```11.0``` if you set it to ```True```, set it to ```False``` if you want the community version of Odoo 11.<br/>

سيتم تثبيت إصدار  <br />
Enterprise <br />
أعلى "" 11.0 "" إذا قمت بتعيينه على  <br />
```True```  <br />
،  قم بتعيينه على  <br />
```False```  <br />
إذا كنت تريد إصدار مجتمع 
Odoo 11. <br />
#### -----------------------------------------
```OE_SUPERADMIN``` 
is the master password for this Odoo installation.<br/>
هي كلمة المرور الرئيسية لتثبيت  <br/>
Odoo. <br/>

#### -----------------------------------------

#### 3. Make the script executable
#### 3. اعط صلاحية التنفيذ للملف

```
sudo chmod +x odoo_install.sh
```
##### 4. Execute the script:
##### 4. قم بتنفيذ الملف
```
sudo ./odoo_install.sh
```
