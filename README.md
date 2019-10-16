# Mikrotik

<< Ad Blocker >>

--adBlock.example.txt
Example of script for mikrotik, System → Scripts → Add New and put content and save, then run.

---- hostScriptUrl - url to blocked resources (dns static resources) in next format:


/ip dns static

add address=127.0.0.1 name=vkontakte.ru comment=For faster loading

--list_13000records.txt

File in mikrotik format for blocking resources.

--Regex for DNS static blocker (add regexp=".*youtube.*" address=127.0.0.1)
1. .*\\.youtube\\.com blocked access to all parts in domain youtube.com.
2. .*youtube\\.com will be blocked everything which end to youtube.com
3. .*youtube.* will be blocked all resources if name contains youtube.

