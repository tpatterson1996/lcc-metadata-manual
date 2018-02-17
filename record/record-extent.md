# Record Extent

---

> ![](/assets/project_required_small.png)**Record Extent is required for Projects Only**

**Record Extent** refers to geographic bounds for the project. It is recommended that you use an extent since they can be used to populate Congressional districts once that capability is available.

![](/assets/extent_screenshot.png)

You can draw a polygon or a bounding box in the initial window. The can be used to describe the extremes of the project or product boundries \(I.E. The outermost latitude and longitude of the extent\).

Clicking the **Edit Extent Features** button allows for the addition of **Feature Properties **such as: **ID**; **Name**; or **Description**.

You can also drag and drop or use the **Import Feature** button to import geoJSON, shapefiles, and kml to describe the exact extent features.

The **Export Features **button can be used to export your extent features as an mdJSON file.

> ![](/assets/note_small.png)  
> **Note**: File attributes \(such as name and description\), will not be imported and must be added manually.  
>   
> **Note: **Bounding boxes will not work across dateline. However, you can have more than one extent, so if your area crosses a dateline, split the area and create separate extents.  
>   
> **Note**: The extent must use geographic coordinates, not projected coordinates
>
> ![](/assets/best_practice_small.png)
>
> **Best Practice**: If you are unsure of your projects extent, enter the coordinates of your LCC boundary in the bounding box.
>
> **Best Practice: **Shapefiles are limited to 5000 vertices. It is recommend that you create only simple polygons or bounding boxes. If you want greater detail, attach high-definition shapefiles instead of trying to draw them.
>
> **Best Practice: **Extents should be accurate enough for searching purposes, but remember that they are metadata, not data.

![](/assets/edit_extent_page.png)

