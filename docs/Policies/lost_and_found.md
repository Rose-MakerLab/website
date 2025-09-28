# Lost & Found Policy

Use the slips provided in MakerLab. 

If we have run out of slips, you can print one [from the PDFs here](../Public%20Documents/project_slip_printout.md).

??? note "Background Information"
    **Authority:** MakerLab Officers

## Leaving Items in the MakerLab
If you need to leave something in the MakerLab and the provided totes and bins do not fit your needs, you may do so temporarily. You must identify the object with a “Project Slip” (see below).

- The Project Slip must be filled out, clearly visible, and near the project. Physically attach the slip to the project if possible.
- Maximum Pickup Period:
    - **3D Print:** 1 week
    - **Other:** 3 days
- Date Format: `MM/DD/YYYY` (e.g. March 14, 1592 → 03/14/1592)

## Lost & Found Procedure

``` mermaid
graph TD
    start0@{ shape: sm-circ, label: "Small start" } --> B;
    B[Non-MakerLab item found in MakerLab] --> C{{Is a project slip nearby?}};
    C ---->|No| D[Post a photo in #lost-and-found and put it in the lost and found bin under the BN-20 near the gray cabinet. It can remain there for TWO WEEKS];
    C ---->|Yes| E{{Does the label have contact info, a placed data, and a pickup date?}};
    E ---->|No| F["Notify the person on the label (if possible)"];
    F --> D;
    E ---->|Yes| G{{Has the date on the label passed?}};
    G ---->|No| H[Leave it be/set aside. Let person know if we moved project totes.];
    H --> stop0@{ shape: framed-circle, label: "Stop" };
    G ---->|Yes| F;
    D --> I["If two weeks pass and it remains unclaimed, it will be handed over to APO Lost and Found, Pubsafe, or if it is a small project (like abandoned prints or other craft-like items) then it will be thrown away"];
    I --> stop1@{ shape: framed-circle, label: "Stop" };
```