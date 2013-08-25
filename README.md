sublime url protocol for mac os x
========================

Supports opening subl:// urls from whoops! php error logs on mac os x

![http://i.imgur.com/C8QKIOo.png](http://i.imgur.com/C8QKIOo.png)

subl://open?url=file://%2FUsers%2FJoel%2FSites%2Fskeleton%2Fhttpdocs%2Fdoc%2Findex.php&line=41

---

Make sure you have `Rack` installed by running 
```bash
sudo gem install rack
```

This only works for Sublime Text 3, to make this work with Sublime Text 2 - alter the `/Sublime%20Protocol.app/Contents/Resources/Scripts/main.scpt` file