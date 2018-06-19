# Professional Services Dept.

This small script provides a format to have imapsync iterate through a list.

Example Format:
$HOST1 $USER1 $PASSWORD1 $HOST2 $USER2 $PASSWORD2\
mail.domain.com admin@domain.com password123 mail.ipage.com admin@ipage.com password123\
mail.domain.com alex@domain.com password123 mail.ipage.com alex@ipage.com password123\
mail.domain.com bob@domain.com password123 mail.ipage.com bob@ipage.com password123

After iterating through the list it will grep through the logs to find if it was successful and displays how many emails were migrated.
