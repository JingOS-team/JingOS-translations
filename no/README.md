# JingOS-translations
JingOS translations files


If you want to translate our text into your local language, you can do this:

```
1 step:

Enter the project folder you want to translate

E.g:
cd [file name]/po
```

```
2 step:

Create a catalog with reference to the country language code

E.g:
mkdir zh_CN
```

```
3 step:

Copy the .po files in other language directories to the directory you created

E.g:
cp zh_CN/*.po [The directory you created]
```

```
4 step:

cd [The directory you created] Modify the .po file

In the po file, “msgid“ represents the original string name before translation, the “msgid“ default is English,  
and “msgstr” represents the local language you need to translate to
```

```
5 step:

Submit to github
```
