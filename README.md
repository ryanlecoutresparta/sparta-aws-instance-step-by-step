### Step by Step of Using AWS to create and run a machine.

1. Log in to your AWS account.
2. Click Services in the Nav Bar.
3. Under the Compute heading, click on EC2.
4. Click on the AMI you'd like to use by clicking it's 'select' button.
5. Choose the instance type you want, then click 'next' in the bottom right corner.
6. Do not change anything on the Configure Instance Details or Add Storage pages; just click next on both.
7. On the Add Tags page, add a new tag by clicking the Add Tag button.
8. In the Key column, type 'Name', and in the Value column, type your chosen name.
9. Once done with step 8, click next in the bottom right again.
10. On the Configure Security Group page, ensure that the security group name is 'launch-wizard-1'.
11. In the Source column, change the dropdown to 'My IP'. After this is done, click 'Review and Launch'.
12. In the Review Instance Launch page, just click Launch in the bottom right.
13. In the modal, ensure the first dropdown has 'Choose an Existing Key Pair' selected, and the second dropdown has 'DevOpsStudent' selected. After this, click Launch Instance.
14. Click on your name, and copy the Public DNS (on the right) to clipboard. Ask your line manager for the key that you need.
15. Go in to your terminal, and enter your home directory.
16. Type in 'ssh -i ~/.ssh/DevOpsStudents.pem ubuntu@' followed by pasting the Public DNS you copied to clipboard earlier.
