# OTP-validation

Admin Portal For Fee Management
This project is a simple Fee Management System that allows an admin to manage student fee statuses and send email notifications regarding pending or cleared fees. It includes OTP-based authentication for secure access.

Features:

1.OTP-based authentication for admin login

 >>>The admin must enter the correct username{admin} and enter a valid OTP sent to the given user email address for login. 

2.Ability to edit student fee status

 >>>The admin can update the fee payment status of students.(from pendingfee - cleared fee)

3.Sends emails to students with pending fees

 >>>The admin can able to send mails who are not cleared their fees.

4.Sends emails to students who have cleared fees
 >>>The admin can able to send mails who clear their pending fees.

Prerequisites:
1.Python 3.x
2.Exteral modules:
 >feepending (send mails for feepending students)
 >feepaid (send mails for feecleared students)
 >otp (To generate otp for validation)

How to Use

1.Run main.py:- Execute the script in your terminal.

2.Enter the admin username (admin)
    > Otp send to your resistered E-mail
    > Check your email for OTP and enter valid otp to log in
    
3.Choose an option:
   >Edit student fee status
   >Send fee pending notifications
   >Send fee cleared notifications

4.Exit:- To close the portal
