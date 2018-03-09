# Project Entry Guidance: Extent Tab

---

**Record Extent** refers to geographic bounds for the project. It is recommended that you use an extent since they can be used to populate Congressional districts once that capability is available. Adding an extent lets LCC staff know the location of your project or product, as well as giving the ability to find your project or product when searching for items in a geographic range.

---

![](/assets/extent_screenshot.png)

Clicking the **Edit Extent Features **button allows for the addition of **Feature Properties **such as: **ID**; **Name **; or **Description**. You can draw polygon or a bounding box in the initial window.

It is possible to export bound features and re-use for other records using the **import feature **button or by dragging and dropping onto the map \(i.e. set up standard geographies\). Features such as geoJSON, shapefiles, and kml can be imported. However, file attributes \(such as name and description\), will not be imported.

### **General Notes & Best Practices**

![](/assets/best_practice_small.png)![](/assets/note_small.png)

| Best Practice: | Notes: |
| :--- | :--- |
| If you are unsure of your projects extent, enter the coordinates of your LCC boundary in the bounding box. | File attributes \(such as name and description\), will not be imported and must be added manually. |
| Shapefiles are limited to 5000 vertices. It is recommend that you create only simple polygons or bounding boxes. If you want greater detail, attach high-definition shapefiles instead of trying to draw them. | The extent must use geographic coordinates, not projected coordinates |
| Extents should be accurate enough for searching purposes, but remember that they are metadata, not data. | Bounding boxes will not work across dateline. However, you can have more than one extent, so if your area crosses a dateline, split the area and create separate extents. |

![](/assets/edit_extent_page.png)

> Consult the [**Record Extent**](https://adiwg.gitbooks.io/mdeditor/content/record/edit/record-extent.html) section of the full mdEditor manual for instructions on adding additional information into the Extent Tab.



