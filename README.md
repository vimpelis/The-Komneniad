# The-Komneniad
The Komneniad is an alternate history mod that aims to combine the extensive flavor of newer mods with the vanilla feel of Victoria II.
It is inspired by various mods from all Paradox games, and features many scenarios that are often overlooked in Victoria II alternate history mods,
such as a colonial Mali Empire, an Ethiopian conquest of the Middle East, and a united West Slavic state.

What is the mod about?
	The Komneniad is not centered on a specific point of divergence. While it may technically exist, it is of absolutely no importance,
	since the map was created based on what the developer thought seemed cool, be it satisfying borders, potentially interesting gameplay
	opportunities or less explored alternate history scenarios. It is a mish-mash of all of your favourite (and not) alt-hist universes,
	with small pieces of inspiration taken from all time periods and all Paradox games.

Then why is it called "The Komneniad"?
	During the development process, it just so turned out that at large, the European politics were dictated by the actions of the Byzantine Empire. 
	With there being no other unifying quality between all of the features of the mod, it was chosen to name the whole thing after the Byzantines.
	Besides, doesn't that eagle on the logo look cool?

Where can I find the lore?
	Small pieces of lore are scattered among the mod's hundreds of events, with most countries having a starting event with a short lore dump.
	Pretty much all you need to know when getting into the mod is that the defining event of the last few decades were the Martletist Wars,
	the in-universe version of the OTL French Revolutionary Wars. The symbol of the revolution in this mod, the Martlet, is an ancient heraldic
	image found in England - it is a bird with no legs, thus being unable to land. It represents England's centuries-long struggle against
	the various invaders, most notably the Danes, who ruled England since the 12th century.
	
The other important things to know are:
	- The mod is based on GFM, so all credits to the GFM devs for a major part of the content. However, since the mod has been in development for
	  quite a while, the exact GFM version is from somewhere around July 2023, so a lot of newer content isn't in.
	- The Komneniad is a one-man project, and thus, while I will try to keep regularly updating the mod, don't expect exceptional speed.
	- While the mod is in its infancy, many things are subject to change, so feel free to propose stuff you'd like to see,
	  even if it's on a level of completely removing a tag.
	- The mod does not support ANY other languages than English. You will get a lot of weird loc if you play in a different language.
	- GFM Dismantlement is turned off for now, since configuring it is quite a task. And considering the system was surgically cut, the default
	  dismantlement that replaced it could be a bit wonky. Use with caution.
	- Dynamic Colonial Governments have been turned off for obvious reasons.
	- You can't use Demand Concession on any East Asian country until Nat. and Imp.
	- Some African provinces will have their goods changed if the owner has researched Organic Chemistry and the year is after 1890. This is done
	  automatically through monthly cleanup. See the bottom of this file for specific province IDs.
	- Make sure to check out new African post-colonial tags! Cores of them appear after 1890 (and only if the corresponding region is consolidated).
	
WARNING: Playing in small resolutions will cause problems with the main menu. The recommended resolution is 1920x1200 and above.


Country tags:

EUROPE:
CLT - Celtic Union
DAN - Daneland
LON - London
BRB - Brabant
HLL - Holland
ADU - Andalusia
ARE - Arles
WES - Westphalia
ZPD - Zapadoslavia
BYZ - Byzantium
NSB - North Sea Union
BNE - Bern
STT - Stettin
WLG - Wolgast
FRK - Franconia
SIE - Transylvania
LOM - League of Milan
THU - Thuringia
ZAP - Zaporozhie
BAE - Balearic Islands
GOT - Gotland
VID - Vidzeme
DOR - Dorpat
KUR - Courland

EUROPEAN FORMABLES:
LTN - Latin Empire
DIE - Dietsland
WST - Westland
CRP - Carpathia

ASIA:
UQA - Al-Uqaydat
ZND - Zandiyeh
MGT - Manghits
MGW - Maguindanao
VOC - United East India Company
PHI - Phimai
LIG - Ligor
IRY - Iryai
HUB - Hubei
HEB - Hebei
JIA - Jiangxi
CMP - Champa
YUE - Yue
FJN - Min

ASIAN FORMABLES:
XIE - Xie
TUT - Tultaehan

NEW WORLD:
WEL - Welserland
SAH - Sahel Al-Wafir
BIR - Biru
AYL - Ayllonia
VRI - Vrijland
ILD - Ildathach
ACA - Acadia
TGZ - Taguzgalpa
NBS - Vaskonia Berria
FLU - Fluvial
IRO - Northw. Conf.

NEW WORLD FORMABLES:
CLM - Colombia
AAL - Ard Al-Hurriyah


Event ID ranges:
150000 - Iberia
151000 - Byzantium
152000 - Russia
153000 - Carpathia
153200 - Hungary
154000 - ZPD
155000 - Germany
156000 - Brabant
157000 - British Isles
158000 - Northern Colombia
159000 - Hispanic Colombia
160000 - RUS-BYZ diplo
161000 - Ard Alhuriya
162000 - Antarctic
163000 - Afghanistan
164000 - India
165000 - China
166000 - SEAsia
167000 - South Africa
168000 - Arabia
169000 - Debug
170000 - Italy
171000 - Arles
172000 - France
173000 - Arajana

Random notes that are not present in any of the events:

	The name of the Korean formable, Tultaehan (Duldaehan in Revised Romanization of Korean), means "Two Great Han", in reference to the Han Chinese
	and the name that is sometimes used to refer to Korea (Han). You could also translate it as "two for one", which also fits I guess.

	California is pretty overextended at the start of the game since they just recently annexed a lot of land around Idaho and the Salt Lake.
	This means they don't really care about expanding further into the continent.


African provinces trade goods changes (after 1890):
1935 = { trade_goods = coal } #Aruchukwu (representing Enugu)
1949 = { trade_goods = coal } #Hadejia
2054 = { trade_goods = coal }
2072 = { trade_goods = coal }
2073 = { trade_goods = coal }

1991 = { trade_goods = ivory }

1886 = { trade_goods = grain } #Bo
1809 = { trade_goods = grain } #Say
2017 = { trade_goods = grain }

1878 = { trade_goods = timber }

2075 = { trade_goods = gold } #Francistown gold
1881 = { trade_goods = gold } #Dinguiraye
1909 = { trade_goods = gold } #Sekondi (Tarkwa Mine)
1910 = { trade_goods = gold } #Kumai (Obuasi Mine)

3678 = { trade_goods = sugar }
2050 = { trade_goods = sugar }
1982 = { trade_goods = sugar }

1879 = { trade_goods = fruit } #Boffa/Conakry
1919 = { trade_goods = fruit }
2039 = { trade_goods = fruit }
2041 = { trade_goods = fruit }
1994 = { trade_goods = fruit }

2031 = { trade_goods = cattle }
2076 = { trade_goods = cattle }
2077 = { trade_goods = cattle }
2574 = { trade_goods = cattle }
3649 = { trade_goods = cattle }

2064 = { trade_goods = tea }
2065 = { trade_goods = tea }
2067 = { trade_goods = tea }
2581 = { trade_goods = tea }
1998 = { trade_goods = tea }
2026 = { trade_goods = tea }
2027 = { trade_goods = tea }
2028 = { trade_goods = tea }
2040 = { trade_goods = tea }
2042 = { trade_goods = tea }

1921 = { trade_goods = tropical_wood }
1922 = { trade_goods = tropical_wood }
random_owned = { limit = { province_id = 1923 NOT = { trade_goods = tropical_wood } } trade_goods = tropical_wood } #Lagos
1924 = { trade_goods = tropical_wood } #Abeokuta
1926 = { trade_goods = tropical_wood } #Ife
1927 = { trade_goods = tropical_wood } #Ilorin
1932 = { trade_goods = tropical_wood } #Bonny
1983 = { trade_goods = tropical_wood }
2118 = { trade_goods = tropical_wood }
2119 = { trade_goods = tropical_wood }
3281 = { trade_goods = tropical_wood }
1978 = { trade_goods = tropical_wood }

1839 = { trade_goods = tobacco }
1945 = { trade_goods = tobacco } #Kano
2009 = { trade_goods = tobacco }
2018 = { trade_goods = tobacco }
2015 = { trade_goods = tobacco }
2053 = { trade_goods = tobacco }
2058 = { trade_goods = tobacco }
2066 = { trade_goods = tobacco }
2068 = { trade_goods = tobacco }
2070 = { trade_goods = tobacco }
2074 = { trade_goods = tobacco }
3677 = { trade_goods = tobacco }

1877 = { trade_goods = rubber }
1880 = { trade_goods = rubber } #Timbo
1882 = { trade_goods = rubber } #Kankan
1883 = { trade_goods = rubber } #Beyla
1928 = { trade_goods = rubber } #Benin
1933 = { trade_goods = rubber } #Awka
1934 = { trade_goods = rubber } #Calabar
1962 = { trade_goods = rubber }
1965 = { trade_goods = rubber }
2063 = { trade_goods = rubber }
1970 = { trade_goods = rubber }
1899 = { trade_goods = rubber } #Bondouku
1975 = { trade_goods = rubber }
1976 = { trade_goods = rubber }
1980 = { trade_goods = rubber }
1981 = { trade_goods = rubber }
1985 = { trade_goods = rubber }
1986 = { trade_goods = rubber }
1992 = { trade_goods = rubber }
1996 = { trade_goods = rubber }

1884 = { trade_goods = coffee } #Freetown
1885 = { trade_goods = coffee } #Falaba
1892 = { trade_goods = coffee }
1893 = { trade_goods = coffee }
1895 = { trade_goods = coffee } #Bouake
1896 = { trade_goods = coffee } #Man
1897 = { trade_goods = coffee } #Akoupe
1907 = { trade_goods = coffee } #Accra
1911 = { trade_goods = coffee } #Kintampo
1912 = { trade_goods = coffee } #Wa
1914 = { trade_goods = coffee } #Lome
random_owned = { limit = { province_id = 1915 } trade_goods = coffee } #Ho
1917 = { trade_goods = coffee } #Atakpame
1936 = { trade_goods = coffee } #Nsukka
1937 = { trade_goods = coffee } #Wukari
1956 = { trade_goods = coffee }
1957 = { trade_goods = coffee }
1958 = { trade_goods = coffee }
1960 = { trade_goods = coffee }
1961 = { trade_goods = coffee }
1968 = { trade_goods = coffee }
1971 = { trade_goods = coffee }
1977 = { trade_goods = coffee } #Brazzaville
1990 = { trade_goods = coffee }
1997 = { trade_goods = coffee }
2000 = { trade_goods = coffee }
2001 = { trade_goods = coffee }
2002 = { trade_goods = coffee }
2003 = { trade_goods = coffee }
2021 = { trade_goods = coffee }
2024 = { trade_goods = coffee }
2032 = { trade_goods = coffee }
2033 = { trade_goods = coffee }
random_owned = { limit = { province_id = 2034 } trade_goods = coffee }
2037 = { trade_goods = coffee }
2044 = { trade_goods = coffee }
2046 = { trade_goods = coffee }
2047 = { trade_goods = coffee }
2051 = { trade_goods = coffee }
2052 = { trade_goods = coffee }
2069 = { trade_goods = coffee }
2115 = { trade_goods = coffee }
2121 = { trade_goods = coffee }
2624 = { trade_goods = coffee }
3610 = { trade_goods = coffee }
3611 = { trade_goods = coffee }
3674 = { trade_goods = coffee }
3675 = { trade_goods = coffee }
3679 = { trade_goods = coffee }

1788 = { trade_goods = cotton }
1791 = { trade_goods = cotton }
1792 = { trade_goods = cotton }
1793 = { trade_goods = cotton }
1794 = { trade_goods = cotton } #Bamako
1795 = { trade_goods = cotton } #Kayes
1797 = { trade_goods = cotton } #Kita
1798 = { trade_goods = cotton } #Bougouni
1799 = { trade_goods = cotton } #Sikasso
1810 = { trade_goods = cotton } #Dosso
1811 = { trade_goods = cotton } #Maradi
1818 = { trade_goods = cotton }
1819 = { trade_goods = cotton }
1820 = { trade_goods = cotton }
1827 = { trade_goods = cotton }
1830 = { trade_goods = cotton }
1898 = { trade_goods = cotton } #Kong
1900 = { trade_goods = cotton } #Odienne
1901 = { trade_goods = cotton } #Wagadugu
1904 = { trade_goods = cotton } #Fada Ngourma
1905 = { trade_goods = cotton } #Bobo Dioulasso
1906 = { trade_goods = cotton } #Orodaro
1913 = { trade_goods = cotton } #Tamale
random_owned = { limit = { province_id = 1916 } trade_goods = cotton } #Yendi
1918 = { trade_goods = cotton } #Sokode
1920 = { trade_goods = cotton }
1939 = { trade_goods = cotton } #Zaria
1940 = { trade_goods = cotton } #Bida
1944 = { trade_goods = cotton } #Gombe
1948 = { trade_goods = cotton } #Sokoto
1950 = { trade_goods = cotton } #Yola
1951 = { trade_goods = cotton } #Kuka
1963 = { trade_goods = cotton }
1964 = { trade_goods = cotton }
1966 = { trade_goods = cotton }
1967 = { trade_goods = cotton }
1995 = { trade_goods = cotton }
2005 = { trade_goods = cotton }
2012 = { trade_goods = cotton }
2016 = { trade_goods = cotton }
2019 = { trade_goods = cotton }
2020 = { trade_goods = cotton }
2022 = { trade_goods = cotton }
2023 = { trade_goods = cotton }
2029 = { trade_goods = cotton }
2030 = { trade_goods = cotton }
random_owned = { limit = { province_id = 2035 } trade_goods = cotton }
2036 = { trade_goods = cotton }
2043 = { trade_goods = cotton }
2059 = { trade_goods = cotton }
2061 = { trade_goods = cotton }
2122 = { trade_goods = cotton }