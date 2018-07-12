# CRC16ForPHP
这是一个CRC16校验算法的PHP代码的实现

目前暂时支持
* MODBUS协议




```
$crc = new CRC16();
$result = $crc->calculationResult('010303000008');
echo $result.PHP_EOL; // 4844
```