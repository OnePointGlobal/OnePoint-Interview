# INavigations.Item Property (NavigationTypes)
 

The index that refers to the <a href="T_OnePoint_Interview_INavigation">INavigation</a> by a <a href="T_OnePoint_Interview_NavigationTypes">NavigationTypes</a>.

**Namespace:**&nbsp;<a href="N_OnePoint_Interview">OnePoint.Interview</a><br />**Assembly:**&nbsp;OnePoint.Interview (in OnePoint.Interview.dll) Version: 1.5.0.0 (1.5.0.0)

## Syntax

**C#**<br />
``` C#
INavigation this[
	NavigationTypes navType
] { get; set; }
```

**VB**<br />
``` VB
Default Property Item ( 
	navType As NavigationTypes
) As INavigation
	Get
	Set
```

**C++**<br />
``` C++
property INavigation^ default[NavigationTypes navType] {
	INavigation^ get (NavigationTypes navType);
	void set (NavigationTypes navType, INavigation^ value);
}
```


#### Parameters
&nbsp;<dl><dt>navType</dt><dd>Type: <a href="T_OnePoint_Interview_NavigationTypes">OnePoint.Interview.NavigationTypes</a><br />The <a href="T_OnePoint_Interview_NavigationTypes">NavigationTypes</a></dd></dl>

#### Return Value
Type: <a href="T_OnePoint_Interview_INavigation">INavigation</a><br />The <a href="T_OnePoint_Interview_INavigation">INavigation</a>.

## See Also


#### Reference
<a href="T_OnePoint_Interview_INavigations">INavigations Interface</a><br /><a href="Overload_OnePoint_Interview_INavigations_Item">Item Overload</a><br /><a href="N_OnePoint_Interview">OnePoint.Interview Namespace</a><br />