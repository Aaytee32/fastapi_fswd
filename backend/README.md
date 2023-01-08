Fastapi FSWD

#How to fix git issues when unable to connect with computer (error with clone or push)

$ssh-keygen
-->Press enter for all the prompts until ida_rsa.pub is generated
-->Navigate to where  ida_rsa.pub is saved and copy string starting with "ssh-rsa..."
-->Go to github>>settings>>ssh and gpg keys>>create new ssh>>give title to new ssh key>>paste string and save.
-->try push or clone again. Viola!