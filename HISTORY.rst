=======
History
=======
2024.10.10 -- Enhancement: Added state method for some widgets
    * Added a state method to LabeledWidget, LabeledComboBox, LabeledEntry, UnitEntry
      and UnitComboBox. This method sets or returns the state of the widget

2024.7.21 -- Return the width of aligned labels
    * The align_labels procedure now returns the width of the labels. This is useful for
      laying out indented widgets.
      
2024.5.1 -- Enhancement to ScrolledColumns
    * Added optional separator columns for dividing sections of the table.
      
2022.10.28 -- Bugfix: problem deleting 2 or more keywords
  There was a crash if you deleted a second keyword in the Keywords tab of
  calculation.

0.1.0 (2019-04-02)
  * First release on PyPI.
