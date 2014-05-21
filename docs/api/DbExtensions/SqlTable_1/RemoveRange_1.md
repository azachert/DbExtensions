SqlTable&lt;TEntity>.RemoveRange Method (IEnumerable&lt;TEntity>, ConcurrencyConflictPolicy)
============================================================================================
Executes DELETE commands for the specified *entities*, using the provided *conflictPolicy*.

**Namespace:** [DbExtensions][1]  
**Assembly:** DbExtensions (in DbExtensions.dll)

Syntax
------

```csharp
public void RemoveRange(
	IEnumerable<TEntity> entities,
	ConcurrencyConflictPolicy conflictPolicy
)
```

### Parameters

#### *entities*
Type: [System.Collections.Generic.IEnumerable][2]&lt;[TEntity][3]>  
The entities whose DELETE commands are to be executed.

#### *conflictPolicy*
Type: [DbExtensions.ConcurrencyConflictPolicy][4]  
The [ConcurrencyConflictPolicy][4] that specifies what columns to check for in the DELETE predicate, and how to validate the affected records value.


See Also
--------
[SqlTable&lt;TEntity> Class][3]  
[DbExtensions Namespace][1]  

[1]: ../README.md
[2]: http://msdn.microsoft.com/en-us/library/9eekhta0
[3]: README.md
[4]: ../ConcurrencyConflictPolicy/README.md