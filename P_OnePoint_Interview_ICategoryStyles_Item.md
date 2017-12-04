# ICategoryStyles.Item Property (CategoryStyleTypes)
 

Gets or sets a category style indexed by a <a href="T_OnePoint_Interview_ICategoryStyle">ICategoryStyle</a>.

**Namespace:**&nbsp;<a href="N_OnePoint_Interview">OnePoint.Interview</a><br />**Assembly:**&nbsp;OnePoint.Interview (in OnePoint.Interview.dll) Version: 1.5.0.0 (1.5.0.0)

## Syntax

**C#**<br />
``` C#
ICategoryStyle this[
	CategoryStyleTypes index
] { get; set; }
```

**VB**<br />
``` VB
Default Property Item ( 
	index As CategoryStyleTypes
) As ICategoryStyle
	Get
	Set
```

**C++**<br />
``` C++
property ICategoryStyle^ default[CategoryStyleTypes index] {
	ICategoryStyle^ get (CategoryStyleTypes index);
	void set (CategoryStyleTypes index, ICategoryStyle^ value);
}
```


#### Parameters
&nbsp;<dl><dt>index</dt><dd>Type: <a href="T_OnePoint_Interview_CategoryStyleTypes">OnePoint.Interview.CategoryStyleTypes</a><br />The index.</dd></dl>

#### Return Value
Type: <a href="T_OnePoint_Interview_ICategoryStyle">ICategoryStyle</a><br />The <a href="T_OnePoint_Interview_ICategoryStyle">ICategoryStyle</a>.

## See Also


#### Reference
<a href="T_OnePoint_Interview_ICategoryStyles">ICategoryStyles Interface</a><br /><a href="Overload_OnePoint_Interview_ICategoryStyles_Item">Item Overload</a><br /><a href="N_OnePoint_Interview">OnePoint.Interview Namespace</a><br />