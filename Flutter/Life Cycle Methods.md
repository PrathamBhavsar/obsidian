[link](https://medium.com/@hadiyaaamir222/lifecycle-of-a-stateful-widget-aece2d56c946)

#### createState()
constructor that initiates the widget which creates the state object for the widget
#### initState()
method called when the widget enters the widget tree
#### didChangeDependencies()
- called immediately after initState() before the build() method
- called when it's parent widget's state changes 
- used when we have to change a widget's state based on it's parent widget's state (without listening to provider)
#### **build**()
- builds the widget's UI based on current state
#### setState()
- triggers a rebuild of the widget when state changes
#### didUpdateWidget()
- called when the widget is rebuilt with updated properties
- called after build so you can compare previous and current widget properties
#### deactivate()
- called when the widget is removed from the tree but might be inserted again
#### dispose()
- called when widget is removed from the tree permanently and releases its resources