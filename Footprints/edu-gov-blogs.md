inurl:.gov+inurl:blog
site:.edu inurl:wp-login.php +blog
site:.gov inurl:wp-login.php +blog
site:.edu inurl:"wp-admin" +login
site:.edu inurl:blog "post a comment"
site:.edu inurl:blog "post a comment" -"comments closed" -"you must be logged in" "keyword"
site:.edu "no comments" +blogroll -"posting closed" -"you must be logged in" -"comments are closed"
site:.gov "no comments" +blogroll -"posting closed" -"you must be logged in" -"comments are closed"
inurl:(edu|gov) "no comments" +blogroll -"posting closed" -"you must be logged in" -"comments are closed"
site:.edu inurl:blog "comment" -"you must be logged in" -"posting closed" -"comment closed"
"keyword" blog site:.edu
keyword +inurl:blog site:.edu