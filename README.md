## Multilanguage Support Stacey CMS and Assemblage r3.
========================
<hr>Multilanguage Support for Stacey CMS and Assemblage it helps you to use
the Stacey CMS template and Assemblage in two different languages.
it adds an asset called language that redirects at the correspondent page in the other language.
</hr>

## TABLE OF CONTENTS

* app/
* content/
* public/
* templates/
* .htaccess
* this README.md
* index.php

## INSTALL

* clone the repository 
  'git clone <https://github.com/luisnicg/multilanguage_stacey_and_assemblage.git>'

* Copy to server, `chmod 777 app/_cache`.

  If you want clean urls, `mv htaccess .htaccess`

* You need to upload two versions of your site:
  one for content/eng/ and one for content/esp/ (English and Spanish in the case of this repo).
* You may want to change the language in use with your chosen two: 
	- you need to edit the name of the folder '/content/eng and /content/esp'.
	- You need to edit the languages variable in '/content/eng/_languages.txt' and '/content/esp/_languages.txt' 
	- You need to edit  the line: 'window.location.href='@root_path/"your_language"/home/'' 

## Sites using it

<http://www.ilmotorediricerca.eu>

## Read More

See <http://staceyapp.com> for more detailed usage information.
See <http://www.yconst.com/web/assemblage/> for more information about Assemblage templates.

## Copyright/License

Copyright (c) 2009 Anthony Kolber. See `LICENSE` for details.
Except PHP Markdown Extra which is (c) Michel Fortin (see `/app/parsers/markdown-parser.inc.php` for details) and
JSON.minify which is (c) Kyle Simpson (see 'app/parsers/json-minifier.inc.php' for details).
jquery.freetile.js which is (c) 2010-2012, Ioannis (Yannis) Chatzikonstantinou.

