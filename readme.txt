HTML för huvudsidan finns i "index.html".

HTML för Login/Register-sidan finns i "login-register.html". Man kan klicka på "My Account" på huvudsidan för att komma till Login/Register-sidan och sen på Kenkatalogotypen för att komma tillbaka till huvudsidan igen.

CSS för de olika avsnitten är uppdelade i separata CSS-filer enligt:

                              0  General, buttons, footer: -------- styles.css
                              1  Navbar: -------------------------- navbar-section.css
                              2  Hero: ---------------------------- hero-section.css
                              3  Information: --------------------- information-section.css
                              4  Categories: ---------------------- categories.section.css
                              5  New Arrivals: -------------------- showcase-sections.css
                              6  New Customer Discount: ----------- promo-section.css
                              7  Featured Products: --------------- showcase-sections.css
                              8  Flash Sale: ---------------------- promo-sections.css 
                              9  Top Sellers: --------------------- showcase-sections.css
                              10 Subscribe ------------------------ subscribe-section.css 
                              11 Login/register ------------------- login-register.css

Samtlig CSS finns även kombinerad i en fil "stylesheet.css" under mappen "/ref".

Sektionerna "Categories" och "Top Sellers" är byggda med grid. Resten av sidan är byggd med flex.

I sektionen "Top Sellers" har jag experimenterat med iframes. Den vänstra, största boxen innehåller en iframe som hämtar en del av sin HTML från filen "showcase.html". 
