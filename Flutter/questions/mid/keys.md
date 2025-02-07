identifiers used by flutter to track widgets while rebuilding the widget tree

they preserve the states of that widget during updates, reducing redundant rebuilds

#### Types

###### GlobalKey
- **For accessing widget state extrenally**
- Used to uniquely identify widgets across the **entire widget tree**
- **Retains state** even when the widget moves within the tree
- Allows access to a widget’s state and methods from outside.
- **eg**:  Managing form validation.
###### LocalKey (Parent of ValueKey & ObjectKey)
- **For trackning widgets in dynamic lists**
- Differentiates widgets in the same position
	-  **ValueKey**
		- Uses primitive value (String, int) to differentiate
		- Simpler
		- **eg**: Tracking items in a ListView when data updates
	-  **ObjectKey**
		- Uses complex object to differentiate
		- Complex
		- **eg**: When objects change but should be recognized as the same
- **eg**:  Managing form validation
**UniqueKey**
- **To force a widget to fully rebuild**
- Generates a new unique key **every time**, forcing the widget to rebuild.
- **eg**: Ensuring complete re-creation of a widget when necessary.