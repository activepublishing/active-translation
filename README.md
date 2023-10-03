Requirements
Pimcore 10.x

# Active Translation Bundle

Bundle for automatically translating all or some of the localized fields in PimCore objects.

Allows you to create glossaries for languages whose glossaries are not managed by Deepl and to create, edit and delete translations in these glossaries.

Widget for monitoring translation consumption

#### How to use:

1.	Click on the « Translate » button

![button](https://github.com/activepublishing/active-translation/assets/26277574/8d053cfa-3aab-4ef1-847a-8f271c1573a7)

2.	Select the source language, the target language and the fields to be translated

![fields](https://github.com/activepublishing/active-translation/assets/26277574/bc298d13-53b6-4717-bc7a-ad38f593475b)

3.	Submit

#### Usage check : 

In the Active Publishing menu, click on "Usage Check". The widget can be launched automatically when you log in. The widget is only accessible to users who have the right to use it

![usage_check](https://github.com/activepublishing/active-translation/assets/26277574/b10398f2-87fe-4529-91a9-88c9776b840d)

#### Glossaries : 

Access the menu to create or edit glossaries. The list of available glossaries depends on the languages available and active in PimCore

![menu](https://github.com/activepublishing/active-translation/assets/26277574/c755ff3e-ddcf-49f6-8a19-1eb6e743a4aa)

List of glossaries and the entries associated with each glossary. Simply add an entry to a glossary and it will appear in the list..

![glossaire](https://github.com/activepublishing/active-translation/assets/26277574/2ebe4020-1473-438a-8801-1bb6f7f492ba)

Add an entry to a glossary:

![glossaire_entry](https://github.com/activepublishing/active-translation/assets/26277574/d7de1277-f810-4ff4-bfd8-482b775395b2)

List of available glossaries. By adding the first entry, the glossary will appear in the glossaries that have been populated with data

![glossaire_entry2](https://github.com/activepublishing/active-translation/assets/26277574/9b7543ea-45fb-4a3b-9459-bfa6a2132164)

#### Configuration :

```yaml
//config.yaml
active_deepl_translation:
    auth_key: {YOUR DEEPL AUTH KEY}
```

### IMPORTANT : 

Don't forget to check that the pimcore dependencies are satisfied in the plugin's composer.json file. Pimcore x or higher is required.
