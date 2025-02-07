

Majorly updated default routing in flutter apps. 

Navigator 1.0 didn't support routing on web
it didn't have a push and pop stack maintenance
harder for deep linking

|Feature|**Navigator 1.0 (Imperative)**|**Navigator 2.0 (Declarative)**|
|---|---|---|
|**Approach**|Stack-based (push/pop)|State-based (UI reflects app state)|
|**Deep Linking**|Hard to manage|Natively supports deep linking|
|**Web URL Sync**|No native support|Supports browser back/forward|
|**Navigation Stack**|Managed manually|Uses `Pages` list for state-based navigation|
|**Back Button Handling**|System-dependent|Full control over back button & pop behavior|
|**Complex Apps**|Becomes hard to manage|Better for dynamic, state-driven apps|

