[![Image](https://www.vipm.io/package/robusto_systems_lib_free_label_to_vi_description/badge.svg?metric=installs)](https://www.vipm.io/package/robusto_systems_lib_free_label_to_vi_description/) [![Image](https://www.vipm.io/package/robusto_systems_lib_free_label_to_vi_description/badge.svg?metric=stars)](https://www.vipm.io/package/robusto_systems_lib_free_label_to_vi_description/)

# Free Label To VI Description (Right-Click Menu Plugin)

This is a right-click menu LabVIEW IDE extension. When right-clicking a free label (a comment) on the block diagram or front panel this tool adds a menu item named "Set as VI Description". When clicking this menu item, the tool copies the text in the free label (comment) and applies it to the VI Description. If the VI Description already contains text, a prompt asks the user for confirmation before overwriting the VI Description.

This tool helps keep in sync the contents of a main free label (comment) on the block diagram or front panel and the VI Description. Such that the same comprehensive description of the VI is available both "inside" the VI (on the BD or FP) and "outside" the VI (in the VI Description/Context Help window).

This package installs one file, named "Free Label To VI Description.llb", to the following location:
\resource\plugins\PopupMenus\edit time panel and diagram

For example, to "C:\Program Files (x86)\National Instruments\LabVIEW 2020\resource\plugins\PopupMenus\edit time panel and diagram"

The LLB contains two VIs: one that adds the "Set as VI Description" item to the right-click menu, and one that executes the action when the menu item is selected.
