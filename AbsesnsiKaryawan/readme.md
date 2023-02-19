This project is a continuation of the project done by the previous group. <br />
This project is my responsibility in the Real Project session as a Front-End Developer during this bootcamp program.<br />

This application was created for the purpose of managing apprentice attendance data. <br />
This application is in the form of a website and mobile application. <br />
For mobile applications intended for employees and web intended for Admin, and Head Admin. <br />
This application was created using the OutSystems Service Studio platform version 11.<br />

This application doesn't need to install anything, users only need to open web and mobile attendance links. <br />
Then, users log in according to their respective roles.<br />

mobile: https://acc-dev.outsystemsenterprise.com/PreviewInDevices/?IsMobilePreview=True&DeviceName=Smartphone&URL=/mpbnc_/MyHRProfile?_ts=638029802640539313<br />

web: https://acc-dev.outsystemsenterprise.com/mpncb4421/Entry1.aspx?_ts=638029802808431313<br />

=MOBILE= <br />
username: melan1@ <br />
npk: 91976 <br />
password: melan1@ <br />

=WEB ADMIN= <br />
username: Evii <br />
npk: 91989 <br />
password: Bena123# <br />

=HEAD= <br />
username: vicky2 <br />
npk: 77777 <br />
password: vicky123# <br />

The Structure <br />
Both mobile and website applications use a database created in an OutSystems module called CoreYolo. 
In the API Logic for mobile we create in the server action folder.
The Logic API required to build the website is contained in the Server Action -> Desktop folder.
It contains entities, attributes that serve to build this application.

The mpbnc_<br />
mpbnc_ is a mobile application to fill in the timesheet of apprentice employees. 
This application uses filling in according to the NPK and password that has been registered in the admin database. 
For Interns, they can use features such as check in, check out, postponed attendance, attendance, edit attendance, and change password.

The Mbncb4421<br />
Mbncb4421 is a web application to database management of the employees. This application is used by 2 roles including admin and head.
Each role must log in first, then will enter the page and get features according to their respective roles.
Admin: View and delete attendance reports, recap attendance in detail.
Head Admin: View attendance reports and recap attendance in detail, make changes to approve and decline status.

Dependencies API<br />
Phase 1: https://documenter.+.com/view/12066956/UzQpwTcT <br />
Phase 2: https://documenter.getpostman.com/view/12066956/2s7YfNCbNd#a78018f2-b1e0-4562-811e-48cc209b2707 <br />

