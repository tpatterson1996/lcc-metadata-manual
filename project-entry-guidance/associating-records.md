# Associating Records: Project

The **Associated** section is used to connect metadata records with each other. This feature should be used when items are related, for example, products are often the result of projects, and projects often have sub-projects. Projects and Products can be linked together by using association. Adding associations gives users the ability to find items that relate to each other in the Science Catalog.

{% hint style="info" %}
In ScienceBase, **Associated Records** are referred to as **Item Associations**.
{% endhint %}

{% hint style="info" %}
Remember: Project-product associations are different than parent-child relationships on ScienceBase.
{% endhint %}

## Create Associations

In mdEditor you can either create the association from the Project record or the Product record. The "Association Type" will define the association from your current record to the linked record. Specifying the "Linked Association Type" will create the association from the other direction.

{% hint style="info" %}
Important: It is recommended you ALWAYS specify the Linked Association Type when you create associations. This will ensure the associations are defined from both directions and be present in the metadata no matter how the metadata is translated or where it is used in the future.
{% endhint %}

If you import records from ScienceBase, the record associations might be automatically created, but sometimes you may have to create the associations manually \(as described below\). Associations can only be made after both project and product records have been created in mdEditor.

| Quick Reference: Creating an Association in a Project Record |
| :--- |
| 1. Select "**product**" from the Association Type drop-down menu. |
| 2. Use the _Select a Record_ button to select an associated product. |
| 3. Choose the product that you would like to associate from the "Select a Resource" list. |
| 4. Fill out the Linked Association Type with "**parentProject**." |

### Step-by-Step: Creating an Association in a Project Record

**Step 1**: Select "**product"** from the **Association Type** drop-down menu. This field will describe the relationship from the associated record to the project record \(the associated record is the product of the project record you are editing\).

![](../.gitbook/assets/product_association_lcc.png)

**Step 2**: Click the "**Select a Record**" button to select an associated product.

![](../.gitbook/assets/select_a_record_button.png)

**Step 3**: Choose the product that you would like to associate from the **Select a Resource** list.

![](../.gitbook/assets/select_a_resource_product_window.png)

**Step 4**: Fill out the Linked Association Type with "**parentProject**."

![](../.gitbook/assets/project_association_linked_record.PNG)

