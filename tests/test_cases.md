# Test Cases – FIT4012 Lab 2

## Caesar Cipher
- [x] Encrypt `I LOVE YOU` với key `3` -> Result: `L ORYH BRX`
- [x] Encrypt `hello world` với key `5` -> Result: `mjqqt btwqi`
- [x] Decrypt `L ORYH BRX` với key `3` -> Result: `I LOVE YOU`

## Rail Fence Cipher
- [x] Encrypt `I LOVE YOU` với `2` rails -> Result: `ILV O OEYU`
- [x] Encrypt `I LOVE YOU` với `4` rails -> Result: `I  EYLVOOU`
- [x] Decrypt một bản mã Rail Fence hợp lệ -> Result: Done (Tested with 2 rails)

## Validation / File input
- [x] Kiểm tra đầu vào không hợp lệ -> Result: Passed (Shows error message)
- [x] Đọc thông điệp từ `data/input.txt` -> Result: Passed (Choice 3 tested)