# cvvc-incision-dict-generator

automaticly generate UTAU Incision Plugin format dictionary from CVVC presamp.ini  
a result of this program:[CVVC夏語遙v3拆音字典檔](https://bowlroll.net/file/245265)

config in cvvc_dict_conf.ini:  
<pre>
[Dict_Setting]
Name=NAME OF DICTIONARY
StaticHead=False
StaticLength=120
IgnoreMaxR=60
[Config]
presamp=LOCATION OF presamp.ini
output=FILE NAME OF OUTPUT
ignore_head=IGNORED PREFIX(SPLIT WITH ,)
ignore_foot=IGNORED SUFFIX(SPLIT WITH ,)
ignore_element=IGNORED ELEMENT(SPLIT WITH ,)
ignore_vowel=IGNORED VOWEL(SPLIT WITH ,)
ignore_consonant=IGNORED CONSONANT(SPLIT WITH ,)
</pre>
settings of Dict_Setting please reference the example file of UTAU Incision
