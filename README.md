# RCE 批量腳本
- Drupal7
```
給予目標 IP target.txt (包含 http/https)，成功後會寫入到 sucess.txt 中。
Use: python3 AutoScript.py
```
- 致遠 OA A8 htmlofficeservlet (CNVD-2019-19299)
```
給予目標 IP target.txt (包含 http/https)，自動判斷是否存在弱點，並自動上傳 Webshell，成功後寫入到 sucess.txt 中。
Use: Python3 AutoScript.py
```
- 泛微 OA E-Office OfficeServer.php 任意文件上傳
```
給予目標 IP target.txt (包含 http/https)，並自動上傳 Webshell，成功後寫入到 sucess.txt 中。
Use: Python3 AutoScript.py
```
- 通達OA v2017 action_upload.php 任意文件上傳漏洞
```
給予目標 IP target.txt (包含 http/https)，並自動上傳 Webshell，成功後寫入到 sucess.txt 中。
蟻劍密碼 : cmd(base64)
Use: Python3 AutoScript.py
```
- 萬戶OA OfficeServer.jsp 任意文件上傳漏洞
```
給予目標 IP target.txt (包含 http/https)，自動判斷 URL 狀態是否為 200，並上傳 Webshell，成功後寫入到 upload_ezOFFICE.txt_200.txt 中。
冰蠍 : rebeyond
Use: Python3 AutoScript.py
```
- 泛微 OA E-Office(CNVD-2021-49104) 任意檔案上傳
```
給予目標 IP target.txt (包含 http/https) , 自動上傳 Webshell , 將成功上傳 Webshell 地址寫入到 success.txt
Use : python3 AutoScript.py --upload-pl EOffice-url.txt (批量掃描)
```
