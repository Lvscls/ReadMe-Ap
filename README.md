# PhpMyAdmin

**Introduction**

PhpmyAdmin est un logiciel gratuit en PHP pour administrer un serveur MySQL ou MariaDB.

**Pré-requis**

Pour utiliser PhpmyAdmin il faut un serveur web comme Apach ou IIS

Il faut également :
- Php 7.1.3
- Mbstring extension
- l'extension zip php
- Une base de donnée MySQL 5.5 ou une version plus récente , MariaDB 5.5 ou une version plus récente.
- Un navigateur web avec cookie et Javascript

**Installation**

Le moyen le plus simple d'obtenir phpMyAdmin sur Windows consiste à utiliser des produits tiers qui incluent phpMyAdmin avec une base de données et un serveur Web tels que [WAMPSERVER](https://www.wampserver.com/)

**Auteur**

phpMyAdmin est Open Source, vous êtes donc invité à y contribuer. De nombreuses fonctionnalités intéressantes ont été écrites par d'autres personnes et vous pouvez également contribuer à faire de phpMyAdmin un outil utile.

**Crédit**

Tobias Ratschiller <tobias_at_ratschiller.com>
creator of the phpMyAdmin project
maintainer from 1998 to summer 2000
Marc Delisle <marc_at_infomarc.info>
multi-language version in December 1998
various fixes and improvements
first version of the SQL analyser (most of it)
maintainer from 2001 to 2015
Olivier Müller <om_at_omnis.ch>
started SourceForge phpMyAdmin project in March 2001
sync’ed different existing CVS trees with new features and bugfixes
multi-language improvements, dynamic language selection
many bugfixes and improvements
Loïc Chapeaux <lolo_at_phpheaven.net>
rewrote and optimized JavaScript, DHTML and DOM stuff
rewrote the scripts so they fit the PEAR coding standards and generate XHTML1.0 and CSS2 compliant codes
improved the language detection system
many bugfixes and improvements
Robin Johnson <robbat2_at_users.sourceforge.net>
database maintenance controls
table type code
Host authentication IP Allow/Deny
DB-based configuration (Not completed)
SQL parser and pretty-printer
SQL validator
many bugfixes and improvements
Armel Fauveau <armel.fauveau_at_globalis-ms.com>
bookmarks feature
multiple dump feature
gzip dump feature
zip dump feature
Geert Lund <glund_at_silversoft.dk>
various fixes
moderator of the phpMyAdmin former users forum at phpwizard.net
Korakot Chaovavanich <korakot_at_iname.com>
“insert as new row” feature
Pete Kelly <webmaster_at_trafficg.com>
rewrote and fix dump code
bugfixes
Steve Alberty <alberty_at_neptunlabs.de>
rewrote dump code for PHP4
mySQL table statistics
bugfixes
Benjamin Gandon <gandon_at_isia.cma.fr>
main author of the version 2.1.0.1
bugfixes
Alexander M. Turek <me_at_derrabus.de>
MySQL 4.0 / 4.1 / 5.0 compatibility
abstract database interface (PMA_DBI) with MySQLi support
privileges administration
XML exports
various features and fixes
German language file updates
Mike Beck <mike.beck_at_web.de>
automatic joins in QBE
links column in printview
Relation view
Michal Čihař <michal_at_cihar.com>
enhanced index creation/display feature
feature to use a different charset for HTML than for MySQL
improvements of export feature
various features and fixes
Czech language file updates
created current website for phpMyAdmin
Christophe Gesché from the “MySQL Form Generator for PHPMyAdmin” (https://sourceforge.net/projects/phpmysqlformgen/)
suggested the patch for multiple table printviews
Garvin Hicking <me_at_supergarv.de>
built the patch for vertical display of table rows
built the Javascript based Query window + SQL history
Improvement of column/db comments
(MIME)-Transformations for columns
Use custom alias names for Databases in left frame
hierarchical/nested table display
PDF-scratchboard for WYSIWYG- distribution of PDF relations
new icon sets
vertical display of column properties page
some bugfixes, features, support, German language additions
Yukihiro Kawada <kawada_at_den.fujifilm.co.jp>
japanese kanji encoding conversion feature
Piotr Roszatycki <d3xter_at_users.sourceforge.net> and Dan Wilson
the Cookie authentication mode
Axel Sander <n8falke_at_users.sourceforge.net>
table relation-links feature
Maxime Delorme <delorme.maxime_at_free.fr>
PDF schema output, thanks also to Olivier Plathey for the “FPDF” library (see <http://www.fpdf.org/>), Steven Wittens for the “UFPDF” library and Nicola Asuni for the “TCPDF” library (see <https://tcpdf.org/>).
Olof Edlund <olof.edlund_at_upright.se>
SQL validator server
Ivan R. Lanin <ivanlanin_at_users.sourceforge.net>
phpMyAdmin logo (until June 2004)
Mike Cochrane <mike_at_graftonhall.co.nz>
blowfish library from the Horde project (withdrawn in release 4.0)
Marcel Tschopp <ne0x_at_users.sourceforge.net>
mysqli support
many bugfixes and improvements
Nicola Asuni (Tecnick.com)
TCPDF library (<https://tcpdf.org>)
Michael Keck <mkkeck_at_users.sourceforge.net>
redesign for 2.6.0
phpMyAdmin sailboat logo (June 2004)
Mathias Landhäußer
Representation at conferences
Sebastian Mendel <cybot_tm_at_users.sourceforge.net>
interface improvements
various bugfixes
Ivan A Kirillov
new relations Designer
Raj Kissu Rajandran (Google Summer of Code 2008)
BLOBstreaming support (withdrawn in release 4.0)
Piotr Przybylski (Google Summer of Code 2008, 2010 and 2011)
improved setup script
user preferences
Drizzle support
Derek Schaefer (Google Summer of Code 2009)
Improved the import system
Alexander Rutkowski (Google Summer of Code 2009)
Tracking mechanism
Zahra Naeem (Google Summer of Code 2009)
Synchronization feature (removed in release 4.0)
Tomáš Srnka (Google Summer of Code 2009)
Replication support
Muhammad Adnan (Google Summer of Code 2010)
Relation schema export to multiple formats
Lori Lee (Google Summer of Code 2010)
User interface improvements
ENUM/SET editor
Simplified interface for export/import
Ninad Pundalik (Google Summer of Code 2010)
AJAXifying the interface
Martynas Mickevičius (Google Summer of Code 2010)
Charts
Barrie Leslie
BLOBstreaming support with PBMS PHP extension (withdrawn in release 4.0)
Ankit Gupta (Google Summer of Code 2010)
Visual query builder
Madhura Jayaratne (Google Summer of Code 2011)
OpenGIS support
Ammar Yasir (Google Summer of Code 2011)
Zoom search
Aris Feryanto (Google Summer of Code 2011)
Browse-mode improvements
Thilanka Kaushalya (Google Summer of Code 2011)
AJAXification
Tyron Madlener (Google Summer of Code 2011)
Query statistics and charts for the status page
Zarubin Stas (Google Summer of Code 2011)
Automated testing
Rouslan Placella (Google Summer of Code 2011 and 2012)
Improved support for Stored Routines, Triggers and Events
Italian translation updates
Removal of frames, new navigation
Dieter Adriaenssens
Various bugfixes
Dutch translation updates
Alex Marin (Google Summer of Code 2012)
New plugins and properties system
Thilina Buddika Abeyrathna (Google Summer of Code 2012)
Refactoring
Atul Pratap Singh (Google Summer of Code 2012)
Refactoring
Chanaka Indrajith (Google Summer of Code 2012)
Refactoring
Yasitha Pandithawatta (Google Summer of Code 2012)
Automated testing
Jim Wigginton (phpseclib.sourceforge.net)
phpseclib
Bin Zu (Google Summer of Code 2013)
Refactoring
Supun Nakandala (Google Summer of Code 2013)
Refactoring
Mohamed Ashraf (Google Summer of Code 2013)
AJAX error reporting
Adam Kang (Google Summer of Code 2013)
Automated testing
Ayush Chaudhary (Google Summer of Code 2013)
Automated testing
Kasun Chathuranga (Google Summer of Code 2013)
Interface improvements
Hugues Peccatte
Load/save query by example (database search bookmarks)
Smita Kumari (Google Summer of Code 2014)
Central list of columns
Improve table structure (normalization)
Ashutosh Dhundhara (Google Summer of Code 2014)
Interface improvements
Dhananjay Nakrani (Google Summer of Code 2014)
PHP error reporting
Edward Cheng (Google Summer of Code 2014)
SQL Query Console
Kankanamge Bimal Yashodha (Google Summer of Code 2014)
Refactoring: Designer/schema integration
Chirayu Chiripal (Google Summer of Code 2014)
Custom field handlers (Input based MIME transformations)
Export with table/column name changes
Dan Ungureanu (Google Summer of Code 2015)
New parser and analyzer
Nisarg Jhaveri (Google Summer of Code 2015)
Page-related settings
SQL debugging integration to the Console
Other UI improvements
Deven Bansod (Google Summer of Code 2015)
Print view using CSS
Other UI improvements and new features
Deven Bansod (Google Summer of Code 2017)
Improvements to the Error Reporting Server
Improved Selenium testing
Manish Bisht (Google Summer of Code 2017)
Mobile user interface
Remove inline JavaScript code
Other UI improvements
Raghuram Vadapalli (Google Summer of Code 2017)
Multi-table query interface
Allow Designer to work with tables from other databases
Other UI improvements
Maurício Meneghini Fauth
Major improvements and upgrades to the JavaScript core
Modernize JavaScript library functionality
Modernize templating and introduce Twig
William Desportes
Coding style improvements based on PHPStan
Improve links to external MySQL and MariaDB documentation
Numerous other bug fixes
Emanuel Bronshtein
Comprehensive security assessment and suggestions
Lakshya Arora (Google Summer of Code 2018)
Various improvements including:
Integrate user preferences with local storage
Use a modal login after session expiration
Add support for CHECK CONSTRAINTS
and more!
Saksham Gupta (Google Summer of Code 2018)
Automated theme generator tool
Leonardo Strozzi (Google Summer of Code 2018)
Refactoring Twig templates and other internal code improvements
Piyush Vijay (Google Summer of Code 2018)
Modernize the JavaScript code including introducing Webpack, Babel, and Yarn as well as eslint and Jsdoc
And also to the following people who have contributed minor changes, enhancements, bugfixes or support for a new language since version 2.1.0:

Bora Alioglu, Ricardo ?, Sven-Erik Andersen, Alessandro Astarita, Péter Bakondy, Borges Botelho, Olivier Bussier, Neil Darlow, Mats Engstrom, Ian Davidson, Laurent Dhima, Kristof Hamann, Thomas Kläger, Lubos Klokner, Martin Marconcini, Girish Nair, David Nordenberg, Andreas Pauley, Bernard M. Piller, Laurent Haas, “Sakamoto”, Yuval Sarna, www.securereality.com.au, Alexis Soulard, Alvar Soome, Siu Sun, Peter Svec, Michael Tacelosky, Rachim Tamsjadi, Kositer Uros, Luís V., Martijn W. van der Lee, Algis Vainauskas, Daniel Villanueva, Vinay, Ignacio Vazquez-Abrams, Chee Wai, Jakub Wilk, Thomas Michael Winningham, Vilius Zigmantas, “Manuzhai”.

Translators
Following people have contributed to translation of phpMyAdmin:

Albanian

Arben Çokaj <acokaj_at_shkoder.net>
Arabic

Ahmed Saleh Abd El-Raouf Ismae <a.saleh.ismael_at_gmail.com>
Ahmed Saad <egbrave_at_hotmail.com>
hassan mokhtari <persiste1_at_gmail.com>
Armenian

Andrey Aleksanyants <aaleksanyants_at_yahoo.com>
Azerbaijani

Mircəlal <01youknowme_at_gmail.com>
Huseyn <huseyn_esgerov_at_mail.ru>
Sevdimali İsa <sevdimaliisayev_at_mail.ru>
Jafar <sharifov_at_programmer.net>
Belarusian

Viktar Palstsiuk <vipals_at_gmail.com>
Bulgarian

Boyan Kehayov <bkehayov_at_gmail.com>
Valter Georgiev <blagynchy_at_gmail.com>
Valentin Mladenov <hudsonvsm_at_gmail.com>
P <plamen_mbx_at_yahoo.com>
krasimir <vip_at_krasio-valia.com>
Catalan

josep constanti <jconstanti_at_yahoo.es>
Xavier Navarro <xvnavarro_at_gmail.com>
Chinese (China)

Vincent Lau <3092849_at_qq.com>
Zheng Dan <clanboy_at_163.com>
disorderman <disorderman_at_qq.com>
Rex Lee <duguying2008_at_gmail.com>
<fundawang_at_gmail.com>
popcorner <memoword_at_163.com>
Yizhou Qiang <qyz.yswy_at_hotmail.com>
zz <tczzjin_at_gmail.com>
Terry Weng <wengshiyu_at_gmail.com>
whh <whhlcj_at_126.com>
Chinese (Taiwan)

Albert Song <albb0920_at_gmail.com>
Chien Wei Lin <cwlin0416_at_gmail.com>
Peter Dave Hello <xs910203_at_gmail.com>
Colognian

Purodha <publi_at_web.de>
Czech

Aleš Hakl <ales_at_hakl.net>
Dalibor Straka <dalibor.straka3_at_gmail.com>
Martin Vidner <martin_at_vidner.net>
Ondra Šimeček <ondrasek.simecek_at_gmail.com>
Jan Palider <palider_at_seznam.cz>
Petr Kateřiňák <petr.katerinak_at_gmail.com>
Danish

Aputsiaĸ Niels Janussen <aj_at_isit.gl>
Dennis Jakobsen <dennis.jakobsen_at_gmail.com>
Jonas <jonas.den.smarte_at_gmail.com>
Claus Svalekjaer <just.my.smtp.server_at_gmail.com>
Dutch

Voogt <a.voogt_at_hccnet.nl>
dingo thirteen <dingo13_at_gmail.com>
Robin van der Vliet <info_at_robinvandervliet.nl>
Dieter Adriaenssens <ruleant_at_users.sourceforge.net>
Niko Strijbol <strijbol.niko_at_gmail.com>
English (United Kingdom)

Dries Verschuere <dries.verschuere_at_outlook.com>
Francisco Rocha <j.francisco.o.rocha_at_zoho.com>
Marc Delisle <marc_at_infomarc.info>
Marek Tomaštík <tomastik.m_at_gmail.com>
Esperanto

Eliovir <eliovir_at_gmail.com>
Robin van der Vliet <info_at_robinvandervliet.nl>
Estonian

Kristjan Räts <kristjanrats_at_gmail.com>
Finnish

Juha Remes <jremes_at_outlook.com>
Lari Oesch <lari_at_oesch.me>
French

Marc Delisle <marc_at_infomarc.info>
Frisian

Robin van der Vliet <info_at_robinvandervliet.nl>
Galician

Xosé Calvo <xosecalvo_at_gmail.com>
German

Julian Ladisch <github.com-t3if_at_ladisch.de>
Jan Erik Zassenhaus <jan.zassenhaus_at_jgerman.de>
Lasse Goericke <lasse_at_mydom.de>
Matthias Bluthardt <matthias_at_bluthardt.org>
Michael Koch <michael.koch_at_enough.de>
Ann + J.M. <phpMyAdmin_at_ZweiSteinSoft.de>
<pma_at_sebastianmendel.de>
Phillip Rohmberger <rohmberger_at_hotmail.de>
Hauke Henningsen <sqrt_at_entless.org>
Greek

Παναγιώτης Παπάζογλου <papaz_p_at_yahoo.com>
Hebrew

Moshe Harush <mmh15_at_windowslive.com>
Yaron Shahrabani <sh.yaron_at_gmail.com>
Eyal Visoker <visokereyal_at_gmail.com>
Hindi

Atul Pratap Singh <atulpratapsingh05_at_gmail.com>
Yogeshwar <charanyogeshwar_at_gmail.com>
Deven Bansod <devenbansod.bits_at_gmail.com>
Kushagra Pandey <kushagra4296_at_gmail.com>
Nisarg Jhaveri <nisargjhaveri_at_gmail.com>
Roohan Kazi <roohan_cena_at_yahoo.co.in>
Yugal Pantola <yug.scorpio_at_gmail.com>
Hungarian

Akos Eros <erosakos02_at_gmail.com>
Dániel Tóth <leedermeister_at_gmail.com>
Szász Attila <undernetangel_at_gmail.com>
Balázs Úr <urbalazs_at_gmail.com>
Indonesian

Deky Arifianto <Deky40_at_gmail.com>
Andika Triwidada <andika_at_gmail.com>
Dadan Setia <da2n_s_at_yahoo.co.id>
Dadan Setia <dadan.setia_at_gmail.com>
Yohanes Edwin <edwin_at_yohanesedwin.com>
Fadhiil Rachman <fadhiilrachman_at_gmail.com>
Benny <tarzq28_at_gmail.com>
Tommy Surbakti <tommy_at_surbakti.net>
Zufar Fathi Suhardi <zufar.bogor_at_gmail.com>
Interlingua

Giovanni Sora <g.sora_at_tiscali.it>
Italian

Francesco Saverio Giacobazzi <francesco.giacobazzi_at_ferrania.it>
Marco Pozzato <ironpotts_at_gmail.com>
Stefano Martinelli <stefano.ste.martinelli_at_gmail.com>
Japanese

k725 <alexalex.kobayashi_at_gmail.com>
Hiroshi Chiyokawa <hiroshi.chiyokawa_at_gmail.com>
Masahiko HISAKAWA <orzkun_at_ageage.jp>
worldwideskier <worldwideskier_at_yahoo.co.jp>
Kannada

Robin van der Vliet <info_at_robinvandervliet.nl>
Shameem Ahmed A Mulla <shameem.sam_at_gmail.com>
Korean

Bumsoo Kim <bskim45_at_gmail.com>
Kyeong Su Shin <cdac1234_at_gmail.com>
Dongyoung Kim <dckyoung_at_gmail.com>
Myung-han Yu <greatymh_at_gmail.com>
JongDeok <human.zion_at_gmail.com>
Yong Kim <kim_at_nhn.com>
이경준 <kyungjun2_at_gmail.com>
Seongki Shin <skshin_at_gmail.com>
Yoon Bum-Jong <virusyoon_at_gmail.com>
Koo Youngmin <youngminz.kr_at_gmail.com>
Kurdish Sorani

Alan Hilal <alan.hilal94_at_gmail.com>
Aso Naderi <aso.naderi_at_gmail.com>
muhammad <esy_vb_at_yahoo.com>
Zrng Abdulla <zhyarabdulla94_at_gmail.com>
Latvian

Latvian TV <dnighttv_at_gmail.com>
Edgars Neimanis <edgarsneims5092_at_inbox.lv>
Ukko <perkontevs_at_gmail.com>
Limburgish

Robin van der Vliet <info_at_robinvandervliet.nl>
Lithuanian

Vytautas Motuzas <v.motuzas_at_gmail.com>
Malay

Amir Hamzah <amir.overlord666_at_gmail.com>
diprofinfiniti <anonynuine-999_at_yahoo.com>
Nepali

Nabin Ghimire <nnabinn_at_hotmail.com>
Norwegian Bokmål

Børge Holm-Wennberg <borge947_at_gmail.com>
Tor Stokkan <danorse_at_gmail.com>
Espen Frøyshov <efroys_at_gmail.com>
Kurt Eilertsen <kurt_at_kheds.com>
Christoffer Haugom <ph3n1x.nobody_at_gmail.com>
Sebastian <sebastian_at_sgundersen.com>
Tomas <tomas_at_tomasruud.com>
Persian

ashkan shirian <ashkan.shirian_at_gmail.com>
HM <goodlinuxuser_at_chmail.ir>
Polish

Andrzej <andrzej_at_kynu.pl>
Przemo <info_at_opsbielany.waw.pl>
Krystian Biesaga <krystian4842_at_gmail.com>
Maciej Gryniuk <maciejka45_at_gmail.com>
Michał VonFlynee <vonflynee_at_gmail.com>
Portuguese

Alexandre Badalo <alexandre.badalo_at_sapo.pt>
João Rodrigues <geral_at_jonilive.com>
Pedro Ribeiro <p.m42.ribeiro_at_gmail.com>
Sandro Amaral <sandro123iv_at_gmail.com>
Portuguese (Brazil)

Alex Rohleder <alexrohleder96_at_outlook.com>
bruno mendax <brunomendax_at_gmail.com>
Danilo GUia <danilo.eng_at_globomail.com>
Douglas Rafael Morais Kollar <douglas.kollar_at_pg.df.gov.br>
Douglas Eccker <douglaseccker_at_hotmail.com>
Ed Jr <edjacobjunior_at_gmail.com>
Guilherme Souza Silva <g.szsilva_at_gmail.com>
Guilherme Seibt <gui_at_webseibt.net>
Helder Santana <helder.bs.santana_at_gmail.com>
Junior Zancan <jrzancan_at_hotmail.com>
Luis <luis.eduardo.braschi_at_outlook.com>
Marcos Algeri <malgeri_at_gmail.com>
Marc Delisle <marc_at_infomarc.info>
Renato Rodrigues de Lima Júnio <renatomdd_at_yahoo.com.br>
Thiago Casotti <thiago.casotti_at_uol.com.br>
Victor Laureano <victor.laureano_at_gmail.com>
Vinícius Araújo <vinipitta_at_gmail.com>
Washington Bruno Rodrigues Cav <washingtonbruno_at_msn.com>
Yan Gabriel <yansilvagabriel_at_gmail.com>
Punjabi

Robin van der Vliet <info_at_robinvandervliet.nl>
Romanian

Alex <amihaita_at_yahoo.com>
Costel Cocerhan <costa1988sv_at_gmail.com>
Ion Adrian-Ionut <john_at_panevo.ro>
Raul Molnar <molnar.raul_at_wservices.eu>
Deleted User <noreply_at_weblate.org>
Stefan Murariu <stefan.murariu_at_yahoo.com>
Russian

Andrey Aleksanyants <aaleksanyants_at_yahoo.com>
<ddrmoscow_at_gmail.com>
Robin van der Vliet <info_at_robinvandervliet.nl>
Хомутов Иван Сергеевич <khomutov.ivan_at_mail.ru>
Alexey Rubinov <orion1979_at_yandex.ru>
Олег Карпов <salvadoporjc_at_gmail.com>
Egorov Artyom <unlucky_at_inbox.ru>
Serbian

Smart Kid <kidsmart33_at_gmail.com>
Sinhala

Madhura Jayaratne <madhura.cj_at_gmail.com>
Slovak

Martin Lacina <martin_at_whistler.sk>
Patrik Kollmann <parkourpotex_at_gmail.com>
Jozef Pistej <pistej2_at_gmail.com>
Slovenian

Domen <mitenem_at_outlook.com>
Spanish

Luis García Sevillano <floss.dev_at_gmail.com>
Franco <fulanodetal.github1_at_openaliasbox.org>
Luis Ruiz <luisan00_at_hotmail.com>
Macofe <macofe.languagetool_at_gmail.com>
Matías Bellone <matiasbellone+weblate_at_gmail.com>
Rodrigo A. <ra4_at_openmailbox.org>
FAMMA TV NOTICIAS MEDIOS DE CO <revistafammatvmusic.oficial_at_gmail.com>
Ronnie Simon <ronniesimonf_at_gmail.com>
Swedish

Anders Jonsson <anders.jonsson_at_norsjovallen.se>
Tamil

கணேஷ் குமார் <GANESHTHEONE_at_gmail.com>
Achchuthan Yogarajah <achch1990_at_gmail.com>
Rifthy Ahmed <rifthy456_at_gmail.com>
Thai

<nontawat39_at_gmail.com>
Somthanat W. <somthanat_at_gmail.com>
Turkish

Burak Yavuz <hitowerdigit_at_hotmail.com>
Ukrainian

Сергій Педько <nitrotoll_at_gmail.com>
Igor <vmta_at_yahoo.com>
Vitaliy Perekupka <vperekupka_at_gmail.com>
Vietnamese

Bao Phan <baophan94_at_icloud.com>
Xuan Hung <mr.hungdx_at_gmail.com>
Bao trinh minh <trinhminhbao_at_gmail.com>
West Flemish

Robin van der Vliet <info_at_robinvandervliet.nl>
Documentation translators
Following people have contributed to translation of phpMyAdmin documentation:

Albanian

Arben Çokaj <acokaj_at_shkoder.net>
Arabic

Ahmed El Azzabi <ahmedtek1993_at_gmail.com>
Omar Essam <omar_2412_at_live.com>
Armenian

Andrey Aleksanyants <aaleksanyants_at_yahoo.com>
Azerbaijani

Mircəlal <01youknowme_at_gmail.com>
Sevdimali İsa <sevdimaliisayev_at_mail.ru>
Catalan

josep constanti <jconstanti_at_yahoo.es>
Joan Montané <joan_at_montane.cat>
Xavier Navarro <xvnavarro_at_gmail.com>
Chinese (China)

Vincent Lau <3092849_at_qq.com>
罗攀登 <6375lpd_at_gmail.com>
disorderman <disorderman_at_qq.com>
ITXiaoPang <djh1017555_at_126.com>
tunnel213 <tunnel213_at_aliyun.com>
Terry Weng <wengshiyu_at_gmail.com>
whh <whhlcj_at_126.com>
Chinese (Taiwan)

Chien Wei Lin <cwlin0416_at_gmail.com>
Peter Dave Hello <xs910203_at_gmail.com>
Czech

Aleš Hakl <ales_at_hakl.net>
Michal Čihař <michal_at_cihar.com>
Jan Palider <palider_at_seznam.cz>
Petr Kateřiňák <petr.katerinak_at_gmail.com>
Danish

Aputsiaĸ Niels Janussen <aj_at_isit.gl>
Claus Svalekjaer <just.my.smtp.server_at_gmail.com>
Dutch

Voogt <a.voogt_at_hccnet.nl>
dingo thirteen <dingo13_at_gmail.com>
Dries Verschuere <dries.verschuere_at_outlook.com>
Robin van der Vliet <info_at_robinvandervliet.nl>
Stefan Koolen <nast3zz_at_gmail.com>
Ray Borggreve <ray_at_datahuis.net>
Dieter Adriaenssens <ruleant_at_users.sourceforge.net>
Tom Hofman <tom.hofman_at_gmail.com>
Estonian

Kristjan Räts <kristjanrats_at_gmail.com>
Finnish

Juha <jremes_at_outlook.com>
French

Cédric Corazza <cedric.corazza_at_wanadoo.fr>
Étienne Gilli <etienne.gilli_at_gmail.com>
Marc Delisle <marc_at_infomarc.info>
Donavan_Martin <mart.donavan_at_hotmail.com>
Frisian

Robin van der Vliet <info_at_robinvandervliet.nl>
Galician

Xosé Calvo <xosecalvo_at_gmail.com>
German

Daniel <d.gnauk89_at_googlemail.com>
JH M <janhenrikm_at_yahoo.de>
Lasse Goericke <lasse_at_mydom.de>
Michael Koch <michael.koch_at_enough.de>
Ann + J.M. <phpMyAdmin_at_ZweiSteinSoft.de>
Niemand Jedermann <predatorix_at_web.de>
Phillip Rohmberger <rohmberger_at_hotmail.de>
Hauke Henningsen <sqrt_at_entless.org>
Greek

Παναγιώτης Παπάζογλου <papaz_p_at_yahoo.com>
Hungarian

Balázs Úr <urbalazs_at_gmail.com>
Italian

Francesco Saverio Giacobazzi <francesco.giacobazzi_at_ferrania.it>
Marco Pozzato <ironpotts_at_gmail.com>
Stefano Martinelli <stefano.ste.martinelli_at_gmail.com>
TWS <tablettws_at_gmail.com>
Japanese

Eshin Kunishima <ek_at_luna.miko.im>
Hiroshi Chiyokawa <hiroshi.chiyokawa_at_gmail.com>
Lithuanian

Jur Kis <atvejis_at_gmail.com>
Dovydas <dovy.buz_at_gmail.com>
Norwegian Bokmål

Tor Stokkan <danorse_at_gmail.com>
Kurt Eilertsen <kurt_at_kheds.com>
Portuguese (Brazil)

Alexandre Moretti <alemoretti2010_at_hotmail.com>
Douglas Rafael Morais Kollar <douglas.kollar_at_pg.df.gov.br>
Guilherme Seibt <gui_at_webseibt.net>
Helder Santana <helder.bs.santana_at_gmail.com>
Michal Čihař <michal_at_cihar.com>
Michel Souza <michel.ekio_at_gmail.com>
Danilo Azevedo <mrdaniloazevedo_at_gmail.com>
Thiago Casotti <thiago.casotti_at_uol.com.br>
Vinícius Araújo <vinipitta_at_gmail.com>
Yan Gabriel <yansilvagabriel_at_gmail.com>
Slovak

Martin Lacina <martin_at_whistler.sk>
Michal Čihař <michal_at_cihar.com>
Jozef Pistej <pistej2_at_gmail.com>
Slovenian

Domen <mitenem_at_outlook.com>
Spanish

Luis García Sevillano <floss.dev_at_gmail.com>
Franco <fulanodetal.github1_at_openaliasbox.org>
Matías Bellone <matiasbellone+weblate_at_gmail.com>
Ronnie Simon <ronniesimonf_at_gmail.com>
Turkish

Burak Yavuz <hitowerdigit_at_hotmail.com>
Original Credits of Version 2.1.0
This work is based on Peter Kuppelwieser’s MySQL-Webadmin. It was his idea to create a web-based interface to MySQL using PHP3. Although I have not used any of his source-code, there are some concepts I’ve borrowed from him. phpMyAdmin was created because Peter told me he wasn’t going to further develop his (great) tool.

Thanks go to

Amalesh Kempf <ak-lsml_at_living-source.com> who contributed the code for the check when dropping a table or database. He also suggested that you should be able to specify the primary key on tbl_create.php3. To version 1.1.1 he contributed the ldi_*.php3-set (Import text-files) as well as a bug-report. Plus many smaller improvements.
Jan Legenhausen <jan_at_nrw.net>: He made many of the changes that were introduced in 1.3.0 (including quite significant ones like the authentication). For 1.4.1 he enhanced the table-dump feature. Plus bug-fixes and help.
Marc Delisle <DelislMa_at_CollegeSherbrooke.qc.ca> made phpMyAdmin language-independent by outsourcing the strings to a separate file. He also contributed the French translation.
Alexandr Bravo <abravo_at_hq.admiral.ru> who contributed tbl_select.php3, a feature to display only some columns from a table.
Chris Jackson <chrisj_at_ctel.net> added support for MySQL functions in tbl_change.php3. He also added the “Query by Example” feature in 2.0.
Dave Walton <walton_at_nordicdms.com> added support for multiple servers and is a regular contributor for bug-fixes.
Gabriel Ash <ga244_at_is8.nyu.edu> contributed the random access features for 2.0.6.
The following people have contributed minor changes, enhancements, bugfixes or support for a new language:

Jim Kraai, Jordi Bruguera, Miquel Obrador, Geert Lund, Thomas Kleemann, Alexander Leidinger, Kiko Albiol, Daniel C. Chao, Pavel Piankov, Sascha Kettler, Joe Pruett, Renato Lins, Mark Kronsbein, Jannis Hermanns, G. Wieggers.

And thanks to everyone else who sent me email with suggestions, bug- reports and or just some feedback.

