# Security
该分类为NSString下的Hash分类，提供多种加密方式：</br>

### 散列函数
```objective-c
// 计算MD5散列结果
- (NSString *)md5String;
// 计算SHA1散列结果
- (NSString *)sha1String;
// 计算SHA256散列结果
- (NSString *)sha256String;
// 计算SHA 512散列结果
- (NSString *)sha512String;
```


### HMAC 散列函数
```objective-c
// 计算HMAC MD5散列结果
- (NSString *)hmacMD5StringWithKey:(NSString *)key;
// 计算HMAC SHA1散列结果
- (NSString *)hmacSHA1StringWithKey:(NSString *)key;
// 计算HMAC SHA256散列结果
- (NSString *)hmacSHA256StringWithKey:(NSString *)key;
// 计算HMAC SHA512散列结果
- (NSString *)hmacSHA512StringWithKey:(NSString *)key;
```

### HMAC 文件散列函数

```objective-c
// 计算文件的MD5散列结果
- (NSString *)fileMD5Hash;
// 计算文件的SHA1散列结果
- (NSString *)fileSHA1Hash;
// 计算文件的SHA256散列结果
- (NSString *)fileSHA256Hash;
// 计算文件的SHA512散列结果
- (NSString *)fileSHA512Hash;
```
