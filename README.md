# OTPDemo
OTP  基于时间和密钥生成一次性动态密码


# 调用方法
var totp = new OTPService();
string key =  totp.GetKey();              
string pwd= totp.GetTOTP(key);
