---
title: ITempStore
description: API reference for ITempStore in Vendr, the eCommerce solution for Umbraco
---
## ITempStore

```csharp
public interface ITempStore
```

**Namespace**
* [Vendr.Core.Session](../)

### Methods

#### GetValue&lt;T&gt;

```csharp
public T? GetValue<T>(Guid storeId, string key)
    where T : struct
```


---

#### SetValue&lt;T&gt;

```csharp
public void SetValue<T>(Guid storeId, string key, T? value)
    where T : struct
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->
