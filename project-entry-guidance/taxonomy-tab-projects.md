# Taxonomy Tab: Project

Taxonomy is required for projects and strongly recommended for products \(where applicable\).

| Quick Reference: Project Taxonomy Tab | Required? |
| :--- | :--- |
| Taxonomy | Required if Applicable \(\*New Required Metadata Improvement\) |

## Taxonomy

mdEditor's new “Taxonomy” section automatically pulls in taxonomic information from ITIS \(Integrated Taxonomic Information System – see itis.gov for more information\).

{% hint style="info" %}
Please note that this functionality in mdEditor is not intended to explore ITIS. It is a tool to add known taxonomic information to your metadata. If you want to explore ITIS, go to itis.gov to find information and then come back to mdEditor with the desired search values.
{% endhint %}

The minimum requirements for valid taxonomy are a Taxonomic System plus one or more taxonomic classifications.

### Add Taxonomic System

\(1\) Click "Add Collection"

![](../.gitbook/assets/taxonomy_addcollection.PNG)

\(2\) From here, you can click "Add Taxa from ITIS" directly \(on right side\) without adding the taxonomic system. This will be filled in for you automatically once you have added items from ITIS.

![](../.gitbook/assets/taxonomy_addtaxafromitis.PNG)

\(3\) Enter your search terms in the search box. You can type in a common name, scientific name, or TSN \(Taxonomic Serial Number, assigned by ITIS\). You can type in any level of taxonomy, not just species name \(e.g., you can type in an order or class or genus\). You can specify by Kingdom if you like.

{% hint style="info" %}
If you haven’t used the search in a while \(or ever\) the ITIS service might be asleep so it will take a few more seconds to load but then will load quickly after that.
{% endhint %}

{% hint style="info" %}
The status of the taxonomic classification is denoted in \(\) after the TSN. ITIS may consider a classification "invalid" if the species was reclassified, for example. It is up to you whether you want to add invalid ITIS classifications to your metadata.
{% endhint %}

![](../.gitbook/assets/taxonomy_search_redleggedfrog.PNG)

\(4\) Click "Add" for the search results you want to add to your record and then click "Import Taxa." You will get a message of successful import at the bottom of your screen.

{% hint style="info" %}
You don't need to worry about clicking import multiple times for the same species. mdEditor is smart enough to know not to create duplicate entries of the same species.
{% endhint %}

![](../.gitbook/assets/taxonomy_successfulimport.PNG)

\(5\) Click "Back to Collection." You will see that it has added a taxonomic hierarchy. It has also added a Title to Taxonomic System \(if you hadn’t already added one by hand\). This complete the the minimum information required for taxonomy.

{% hint style="info" %}
You can click on any level of the taxonomic hierarchy to collapse the entries below that level.
{% endhint %}

{% hint style="info" %}
mdEditor only adds common names at the lowest taxonomic level you identified \(e.g., species level\).
{% endhint %}

![](../.gitbook/assets/taxonomy_collection.PNG)

\(6\) You can add additional information regarding the taxonomic information if you desire.

**Observers** would be filled out when there were people who actually went in the field/lab and identified species. Here you would lie the people who did that work.

* General Scope: You can add a description of the range of taxa addressed in the dataset or collection.
* Identification Procedure: You can describe the methods used for taxonomic identification.
* Identification Completeness: You can add information regarding completeness and uncertainty in the identifications.

**Voucher** is where you can add information about specimens you submitted to a museum or a storage facility where you are storing specimens, can document that here \(select a Repository via a Contact entered in mdEditor\).

![](../.gitbook/assets/taxonomy_additionalinfo.PNG)

## When Taxonomy is Needed

Taxonomy is mostly used for search is discovery and functions similar to keywords.

{% hint style="info" %}
If you have existing species names or other keywords, you do not need to delete those. Taxonomy is entered in a separate section in mdJSON so they are separate from Keywords.
{% endhint %}

To some extent, this is up to the judgement of the data manager. You will know best the connection of a resource to a specific species or other taxonomic group. For example, if a bear model was used to rank habitat for a prioritization product but the final output is not relevant to bears any longer, then you probably wouldn't want to add bear species in taxonomy.

## Reporting Issues

If you encounter issues or bugs using the new Taxonomy feature, please report them in this github thread: [https://github.com/adiwg/mdEditor/issues/101](https://github.com/adiwg/mdEditor/issues/101) \(requires github account to post\).

