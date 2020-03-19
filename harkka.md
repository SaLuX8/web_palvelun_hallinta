WordPress CMS julkaisujärjestelmä ja WooCommerce lisäosa  
========================================================
Asennus Ubuntu 18.04 käyttöjärjestelmään
----------------------------------------
Sami Luoma-aho, N4939  
19.3.2020  
TTMS0800 Web-palvelun hallinta harjoitustyö  


[1. Johdanto](#1-johdanto)  
[2. Esivalmistelut](#2-esivalmistelut)  
- [2.1. LAMP](#21-lamp)  
- [2.2. PHP](#22-php)  
- [2.3. MariaDB](#23-mariadb)  

[3. WordPress CMS asennus](#3-wordpress-cms-asennus)  
[4. WooCommerce asennnus](#4-woocommerce-asennnus)  
[5. Johtopäätökset](#5-johtopäätökset)  



# 1. Johdanto  
Testausta  

# 2. Esivalmistelut
\$ sudo apt update  
\$ sudo apt upgrade  
\$ sudo apt install apache2

\$ sudo ufw app list

*Available applications:
  Apache
  Apache Full
  Apache Secure
  OpenSSH*

Komennolla
\$ sudo ufw app info "Apache Full"
nähdään ufw:n valmiin profiilin tiedot. Tiedoista käy ilmi, että ufw:n palomuuriin sallitaan TCP-liikenne portteihin 80 ja 443. Portit ovat http ja ssh -protokollien käyttämät portit.  
\$ sudo ufw allow in "Apache Full"
## 2.1. LAMP
## 2.2. PHP
## 2.3. MariaDB

# 3. WordPress CMS asennus

# 4. WooCommerce asennnus

# 5. Johtopäätökset

Harjoitustyön nimi, tekijöiden nimet, päivämäärä ja tieto siitä, että kyseessä on Verkkopalvelut -opintojakson harjoitustyö.
Tehtävän kuvaus / Johdanto. Esim. "Nykyiset Internetin sovellusprotollat ovat hyvin turvattomia... varsinkin e- kaupankäynnissä on välttämätöntä salata http-liikennettä... https-"protokolla" on ratkaisu; Se... ... Tässä työssä asennetaan Linux alustalle SSL-kykyinen Apache Web-palvelin"
Varsinainen aiheen käsittely. Esim. ohjelmistot käyttöesimerkkeineen
mahdollisesti asennusohjeita (Mistä URLista imuroitiin ja mitä jne..)
mahdollisesti käyttöohjeita ja käyttöesimerkkejä mahdollisine kuvaruutukauppauksineen
Johtopäätökset: "Ohjelma sopii hyvin... Vaikea asennus on Linuxiin tottumattomalle..."
Lähteet