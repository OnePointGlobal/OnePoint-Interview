# INavigations.Item Property (Int32)
 

The index that refers to the <a href="T_OnePoint_Interview_INavigation">INavigation</a> by a zero based pointer.

**Namespace:**&nbsp;<a href="N_OnePoint_Interview">OnePoint.Interview</a><br />**Assembly:**&nbsp;OnePoint.Interview (in OnePoint.Interview.dll) Version: 1.5.0.0 (1.5.0.0)

## Syntax

**C#**<br />
``` C#
INavigation this[
	int index
] { get; set; }
```

**VB**<br />
``` VB
Default Property Item ( 
	index As Integer
) As INavigation
	Get
	Set
```

**C++**<br />
``` C++
property INavigation^ default[int index] {
	INavigation^ get (int index);
	void set (int index, INavigation^ value);
}
```


#### Parameters
&nbsp;<dl><dt>index</dt><dd>Type: System.Int32<br />The zero based index.</dd></dl>

#### Return Value
Type: <a href="T_OnePoint_Interview_INavigation">INavigation</a><br />The <a href="T_OnePoint_Interview_INavigation">INavigation</a>.

## See Also


#### Reference
<a href="T_OnePoint_Interview_INavigations">INavigations Interface</a><br /><a href="Overload_OnePoint_Interview_INavigations_Item">Item Overload</a><br /><a href="N_OnePoint_Interview">OnePoint.Interview Namespace</a><br />