<?php
$sid = 'AC4cf2f3ccf168062c9cd018ca1a772678';
$token = '45b6640133f087459c6343814e60241d';
$number = '+972599466364';

$version = '2010-04-01';

require_once'twilio-php/Services/Twilio.php';

$client = new Services_Twilio($sid, $token, $version);

try {
	$call = $client->account->create(
        $number 
		'+972599466364',
		'http://demo.twilio.com/welcome/voice');
   echo "string";  "Started call: ". $call->sid;
} catch (Exception $e) {
	echo "Error: ". $e->getmessage();
}
