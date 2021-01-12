Update the destructivechanges.xml to specify the correct object to delete, then run the command below.

sfdx force:mdapi:deploy -u rick.arthur@safetynational.com --deploydir . --wait 2 --testlevel RunSpecifiedTests  --runtests SListTest