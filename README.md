# Styletto
android lib to styling app via json files instead of xml

Roadmap:

* several parents for each style: `"parents":["style1","style2","style3"]`
* styles extends chain: `"style1":{"parents":"style2"}, "style3":{"parents:"style1"}`
* import styles files
* override parent style attrs
* merge with current xml styles: override, add items to styles with same name

other stuff:
* multiconfig values in one attrs like `"margin": {"sw640":"20dp", "value":"10dp"}`
* style attr extending strategy `"margin":{"value":"10dp", "provide":"no"}`
* final styles
