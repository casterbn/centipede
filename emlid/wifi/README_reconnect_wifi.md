for reachView 10.0.0

* connect ssh reach 
* create python wifi.py

* cp 

```
cp wifi.py /etc/init.d
chmod +x /etc/init.d/wifi.py
```

* do

```
update-rc.d wifi.py defaults
```

* for delete

```
update-rc.d -f wifi.py remove
```
