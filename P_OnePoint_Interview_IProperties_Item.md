# IProperties.Item Property 
 

The this.

**Namespace:**&nbsp;<a href="N_OnePoint_Interview">OnePoint.Interview</a><br />**Assembly:**&nbsp;OnePoint.Interview (in OnePoint.Interview.dll) Version: 1.5.0.0 (1.5.0.0)

## Syntax

**C#**<br />
``` C#
IProperty this[
	string key
] { get; set; }
```

**VB**<br />
``` VB
Default Property Item ( 
	key As String
) As IProperty
	Get
	Set
```

**C++**<br />
``` C++
property IProperty^ default[String^ key] {
	IProperty^ get (String^ key);
	void set (String^ key, IProperty^ value);
}
```


#### Parameters
&nbsp;<dl><dt>key</dt><dd>Type: System.String<br />The key.</dd></dl>

#### Return Value
Type: <a href="T_OnePoint_Interview_IProperty">IProperty</a><br />The <a href="T_OnePoint_Interview_IProperty">IProperty</a>.

## See Also


#### Reference
<a href="T_OnePoint_Interview_IProperties">IProperties Interface</a><br /><a href="N_OnePoint_Interview">OnePoint.Interview Namespace</a><br />