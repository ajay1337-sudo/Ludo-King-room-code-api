# Ludo-King-room-code-api
Ludo King room code api

http://165.22.211.82:3001/api/roomcode

JSON output - {"room_code":"00856661"}

you can use direct ludo king room code in ludo king game

how to use - 
PHP 
example -
<?php
$resp = file_get_contents('http://165.22.211.82:3001/api/roomcode');

$obj = json_decode($resp);
$token = $obj->room_code;
echo $token 
?>
nodejs
example -
await axios.get('http://165.22.211.82:3001/api/roomcode')
                .then(res => {
                    if (res.status == 200) {
                        localGame.Room_code = res.data.room_code;
                        localGame.save();
                    }
                })
                .catch(err => {
                    console.log(err);
                })
        }

more more info contact me
my email -  	sudo1337@countermail.com
