# Keywords Tab: Product

Adding keywords to your metadata record allows for the record to be found later through a search engine, keywords are the way to tag your projects or products. The mdEditor is designed using thesauruses that contain pre-determined keywords. These thesauruses create a 'controlled vocabulary' so that all LCC staff adding metadata can adhere to the same standards, and future search results can return clear results of projects and products.

| Quick Reference: Product Keywords Tab | Required? |
| :--- | :--- |
| ISO Topic Category | Required |
| LCC End User Types | Required \(\*New Required Metadata Improvement\) |
| GCMD Keywords | Best Practice |

## To add Keywords to your Metadata Record

1. Click “+ Add Thesaurus” on the right to add the different thesauruses.
2. Add keywords from the following pre-populated thesauruses.
3. If none of the keywords in the following categories are sufficient for tagging your record, you can create a custom thesaurus \(see below for more information\).

### LCC Product Required Keywords

#### ISO Topic Category \(Required\)

Because mdJSON metadata is based on the ISO \(International Organization for Standardization\) metadata standard, all LCC projects must select at least one ISO Topic Category. ISO topics were generally meant for spatial data so they might be a bit of a stretch, but do your best to find the best fit. mdEditor provides definitions of each ISO topic category if you hover over the ? icon.

ISO Topic List:

1. biota
2. boundaries
3. climatologyMeteorologyAtmosphere
4. economy
5. elevation
6. environment
7. geoscientificInformation
8. health
9. imageryBaseMapsEarthCover
10. intelligenceMilitary
11. inlandWaters
12. location
13. oceans
14. planningCadastre
15. society
16. structure
17. transportation
18. utilitiesCommunication

{% hint style="info" %}
Tip: Biota and environment are probably the best fit for most LCC projects.
{% endhint %}

#### LCC End User Types \(Required\)

LCC End User Types list:

1. Academics & scientific researchers
2. Conservation NGOs
3. Federal resource managers
4. Hunters & anglers
5. Interested public
6. K-12 students & teachers
7. Other
8. Policy makers & regulators
9. Private land owners
10. Regional & county planners
11. State agencies
12. Tribes

#### GCMD Keywords \(Best Practice\)

GCMD stands for Global Change Master Directory and these keywords are maintained by NASA. Look for useful keywords in the GCMD Science Keywords. There are GCMD Platforms and Instruments Keywords but they are unlikely to apply to LCCs.

{% hint style="info" %}
Best Practice: Check the "Full Path" checkbox to save the full path of the keyword to your metadata. This will maintain the category and context of the specific keywords chosen.
{% endhint %}

## Custom Thesaurus

If any of your desired keywords do not appear in the existing thesauruses, you can add them via the custom thesaurus. Use a custom thesaurus only for keywords that are not available in an existing thesaurus. For example, if a certain end user type is not available in the LCC End User Types thesaurus, you can add the type using the custom thesaurus.

You cannot add keywords to an existing thesaurus; you can only add keywords in a custom thesaurus.

{% hint style="info" %}
You cannot save a custom thesaurus in mdEditor.
{% endhint %}

{% hint style="info" %}
Tip: If you have a consistent set of keywords that you use across your LCC's projects, you could add these to a "template project" record in mdEditor and then modify the specific keywords you need for each project. See the workflow section for more info about using template records.
{% endhint %}

{% hint style="info" %}
Look for useful keywords in the GCMD Science Keywords. GCMD Science keywords would be the only ones applicable to LCCs. There are GCMD Platforms and Instruments but they are unlikely to apply to LCCs.
{% endhint %}

## Keywords and ScienceBase

### Keywords vs. Tags

mdEditor uses the term "keywords" while ScienceBase uses the term "tags."

{% hint style="info" %}
Keywords edited in mdEditor will not overwrite keywords stored in sbJSON on ScienceBase because ScienceBase only adds to the list of tags. If you do not want obsolete keywords/tags to show up on ScienceBase, you will need to manually delete in ScienceBase. mdJSON and the LCC Science Catalog, however, will reflect any changes made in mdEditor.
{% endhint %}

### Imported Keywords

If you imported your product metadata from ScienceBase, then the ScienceBase keywords are each created in a custom thesaurus.

If your LCC already has a controlled vocab list in ScienceBase, unfortunately it cannot connect to mdEditor. The selected keywords for any specific record will import into mdEditor but the saved list will not.

![](../.gitbook/assets/keywords_window.png)

