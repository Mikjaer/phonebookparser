# phonebookparser
Eventphone.de phonebook parser

wget "https://eventphone.de/guru2/phonebook?event=34C3&s=&page=1&format=json"

<code>
 $ php parse.php | grep "[0-9]0[0-9]0"
 3080
 6020
 6050
 7040
 8030
 8040
 8050
 8060
</code>

