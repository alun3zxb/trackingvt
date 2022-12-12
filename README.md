# 安装51tracking V3
composer require alun/trackingvt@dev
# 使用51tracking V3
https://www.51tracking.com/v3/api-index#api-version
`use Tracking\Api as Tapi;`

`$api = new Tapi('you key');`

`$data = ["tracking_numbers" =>"快递单号,快递单号2"];`

`$response = $api->get($data);`


