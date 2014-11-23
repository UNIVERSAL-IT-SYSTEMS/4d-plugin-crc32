4d-plugin-crc32
===============

4D implementation of CRC32

4D Cocoa OX X 10.8+, 32/64 bits, v14+
4D Carbon, OS X 10.6+ (i386), 32 bits, Win32, Win64, v11+

```
C_BLOB($data)

CONVERT FROM TEXT("Hello world!";"us-ascii";$data)

$crc32:=CRC32 Get ($data)

ASSERT($crc32=461707669)
  //http://www.w3schools.com/php/func_string_crc32.asp
```
