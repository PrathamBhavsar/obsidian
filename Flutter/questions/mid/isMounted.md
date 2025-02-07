mounting is the process of putting a widget on the widget tree

the **isMounted** property is a read-only property only available inside the **State** class of a **StatefulWidget**

It prevents errors when calling `setState()` on a widget that **no longer exists**

Used before calling `setState()` inside an **async function**