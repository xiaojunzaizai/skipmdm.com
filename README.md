autobypass-mdm-macbook
Program that have to be downloaded and run in the Rescue Terminal to bypass the mdm remote management lock

Reboot and go into the Recovery Mode by pressinig control r
Once inside make sure your internet is connected
Run below command
curl https://raw.githubusercontent.com/tahseenjamal/autobypass-mdm-macbook/main/autobypass-mdm.sh -o autobypass-mdm.sh && chmod +x ./autobypass-mdm.sh && ./autobypass-mdm.sh
