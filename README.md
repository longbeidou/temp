# temp
临时放资料的地方

$client = new Client(['verify' => false]);  //忽略SSL错误
$response = $client->get($url, ['save_to' => './sdf.jpg']);  //保存远程url到文件
