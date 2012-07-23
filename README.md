ipaddress-for-yii
=================

ipaddress for yii 是用于YII 查询IP所在地的YII extension 采用了新浪IP接口、网易有道IP接口


使用方法 
```
<?php $this->widget('ext.ipaddress.Ipaddress',
		array(
			'ip' => 127.0.0.1,
		));
?>
```
```
echo '127.0.0.1 本机地址';
```