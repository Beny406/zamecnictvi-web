## Pridani fotek
1) Vytvoření folderu (pokud je potřeba) v `assets/img` pomocí tlačítká `create file` Jak na to ukázáno [zde](https://github.com/KirstieJane/STEMMRoleModels/wiki/Creating-new-folders-in-GitHub-repository-via-the-browser). Bohužel nelze vytvořit prázdný folder, takže je potřeba vytvořit s nějakým souborem a pak smazat. 
2) Přidat fotky do `assets/img/{folder_name}` + zmenšené verze s appendixem `_tn`. Lze vytvořit například [zde](http://makethumbnails.com)
3) Přidat description v `_data`. Sekce se musí jmenovat podle adresáře, položka podle image.
4) Přidat řádek do index.html. Např:

        {% include slider.html path="RekonstrukceBalkonu" %}

5) Chvíli trvá, než se stránka znovu zbuildí. Dostupná je poté [zde](https://beny406.github.io/zamecnictvi-web/)
