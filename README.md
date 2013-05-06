
Use locale tag in your url file :

    <locale name="lang" value="fr_FR">
        <url module="home" include="urls_fr.xml" />
        <url module="help" include="urls_fr.xml" />
    </locale>

    <locale name="lang" value="en_EN">
        <url module="home" include="urls_en.xml" />
        <url module="help" include="urls_en.xml" />
    </locale>

