# glFTPd-v2.12-BETA1

```
Change: added support for OpenSSL 3.0
Change: add support for KTLS and SSL_sendfile
Change: removed support for DHPARAM_FILE option
Change: cleanup glftpd.conf parsing for pasv_addr and active_addr
Fix:	Fix infinite loop sometimes happening with load balacing multiple named interfaces
	with active_addr/pasv_addr.
Change: Make "site users" alphabetically sorted.
Change: Site change now supports "xx[m/g/t]" units for max_dlspeed, max_ulspeed, wkly_allotment, max_allot_size. For example "site change username max_dlspeed 2g".
Change: Improved installgl.sh to use "/usr/local/etc" for glftpd on fbsd.
```
