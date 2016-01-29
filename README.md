4d-plugin-crc32
===============

4D implementation of CRC32.

##Platform

| carbon | cocoa | win32 | win64 |
|:------:|:-----:|:---------:|:---------:|
|🆗|🆗|🆗|🆗|


Examples
---

```
C_BLOB($data)

CONVERT FROM TEXT("Hello world!";"us-ascii";$data)

$crc32:=CRC32 Get ($data)

ASSERT($crc32=461707669)
  //http://www.w3schools.com/php/func_string_crc32.asp
```
