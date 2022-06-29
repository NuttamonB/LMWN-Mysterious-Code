# LMWN-Mysterious-Code
LINE MAN Wongnai ชวนคุณชาว DEV Geek 
ร่วมสนุกตอบคำถาม Mysterious Code 
ลุ้นรับ LINE MAN Food Coupon มูลค่า 100 บาท จำนวน 20 รางวัล 
พร้อมลุ้นรับรางวัลสุดพิเศษ on-top เพิ่ม จำนวน 10 รางวัล !!

## Answer the question

	`<?php

	$secret = 'Wae@ajr4ebh&i(rfidn!gAyfo$uD.NSso0fOt$w=a|r1edDxeEvae^l*o9phefrssq.';

	for ($i = 0; $i < strlen($secret); $i += 2) {
   	echo $secret[$i];
	}`

## Answer?
sd, _ := base64.StdEncoding.DecodeString(secret)
result := strings.Replace(string(sd), ":", " ", 5)
for _, v := range result {
	whatIsIt = string(v) + whatIsIt
}
fmt.Println(whatIsIt)
