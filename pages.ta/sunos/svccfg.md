# svccfg

> சேவை உள்ளமைவுகளை இறக்குமதி செய்யவும், ஏற்றுமதி செய்யவும் மற்றும் மாற்றவும்.
> மேலும் விவரத்திற்கு: <https://www.unix.com/man-page/linux/1m/svccfg>.

- உள்ளமைவு கோப்பை சரிபார்க்கவும்:

`svccfg validate {{smf.xml}}`

- கோப்பிற்கு சேவை உள்ளமைவுகளை ஏற்றுமதி செய்யவும்:

`svccfg export {{சேவை_பெயர்}} > {{smf.xml}}`

- கோப்பிலிருந்து சேவை உள்ளமைவுகளை இறக்குமதி/புதுப்பித்தல்:

`svccfg import {{smf.xml}}`