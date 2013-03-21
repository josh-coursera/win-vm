netsh interface ip set address name="Local Area Connection" static 192.168.56.111 255.255.255.0 192.168.0.1 1
&& echo 192.168.56.101 site.dev-coursera.org >>%SystemRoot%\system32\drivers\etc\hosts
&& echo 192.168.56.101 spark.dev-coursera.org >>%SystemRoot%\system32\drivers\etc\hosts

