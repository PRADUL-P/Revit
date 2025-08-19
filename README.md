📖 Copy Filter Overrides (pyRevit Extension)
📌 Overview

This pyRevit extension adds a button to Revit that allows you to copy filter overrides (line color, hatch, fill pattern, transparency, etc.) from one filter in the active view to one or more other filters.

This helps speed up large projects where multiple filters need the same graphic settings.

🔹 Installation Steps

Download and extract the ZIP file into your pyRevit extensions folder:

%appdata%\pyRevit\Extensions


After extraction, the folder structure should look like this:

CopyFilterOverrides.extension
    └── CopyFilterOverrides.tab
        └── Tools.panel
            └── CopyOverrides.pushbutton
                ├── script.py
                ├── script.pushbutton
                └── icon.png (optional)


Open Revit and go to:

pyRevit > Reload

You should now see a new button under the Tools panel:

🔹 Usage Instructions

Open a view that already has filters applied.

Manually set the correct overrides (color, hatch, line type, etc.) on one filter.

Click Copy Filter Overrides.

Select the source filter (the one with correct overrides).

Select one or more target filters (the ones you want to update).

The overrides will be copied automatically. ✅

🔹 Notes

Works per active view (filters must be applied in that view).

If no filters are found, you’ll get an error message.

Multiple target filters can be selected at once.
