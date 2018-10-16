# Project Entry Guidance: Extent Tab

---

**Extent** refers to geographic boundaries for your project. Spatial extents lets users see at a glance the geographic footprint of your project and allows searching within specific geographic areas.

| Quick Reference: Project Extent Tab | Required? |
| :--- |:--- |
| Extent |Required (*New Required Metadata Improvement) |


---

## Creating Extents

There are multiple ways to create a spatial extent for your project.

Clicking the **Edit Extent Features** button allows for the addition of **Feature Properties** such as: **ID**, **Name**, or **Description**. You can draw polygon or a bounding box in the initial window.

You can export spatial extents and re-use for other records using the **import feature** button or by dragging and dropping onto the map. 

Extents are limited to 5000 vertices. Recommend you create only simple polygons or bounding boxes. If you want greater detail, attach high-definition shapefiles instead of trying to draw them.

Extents should be accurate enough for searching purposes, but remember that they are metadata, not data.

### Option 1: Import Spatial Features

Spatial features such as geoJSON, shapefiles, and kml can be imported. However, file attributes \(such as name and description\), will not be imported and must be added manually. 

For projects without an extent, you can use the LCC geography. We will provide geoJSON files for all LCC geographies that you can import into mdEditor. 

{% hint style='info' %} Important: coordinates used must be geographic coordinates, not projected coordinates.{% endhint %}

### Option 2: Draw Spatial Features

{% hint style='tip' %} Tip: It is easier to click "finish" when drawing a polygon instead of trying to close the polygon by clicking on the first point.{% endhint %}

### Option 3: Draw Bounding Box

{% hint style='danger' %}Bounding boxes will not work across the dateline but you can have more than one extent per project. If your project area crosses the dateline, split the area into multiple extents and create separate bounding boxes.{% endhint %}

## Saving and Exporting Extents

{% hint style='tip' %} Tip: You can export, save, and import an extent to use for other projects or products.{% endhint %}



![](/assets/extent_screenshot.png)

![](/assets/edit_extent_page.png)

> For more information, consult the [**Extent**](https://adiwg.gitbooks.io/mdeditor/content/record/edit/record-extent.html) section of the mdEditor manual.



