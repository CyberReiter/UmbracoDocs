---
title: UmbracoAppCache
description: API reference for UmbracoAppCache in Vendr, the eCommerce solution for Umbraco
---
## UmbracoAppCache

```csharp
public class UmbracoAppCache : ICache
```

**Inheritance**

* interface [ICache](../../../vendr-core/vendr-core-cache/icache/)

**Namespace**
* [Vendr.Umbraco.Cache](../)

### Constructors

#### UmbracoAppCache

```csharp
public UmbracoAppCache(IAppCache appCache)
```


### Methods

#### Clear

```csharp
public virtual void Clear(string cacheKey)
```


---

#### ClearAll

```csharp
public virtual void ClearAll()
```


---

#### ClearByKey

```csharp
public virtual void ClearByKey(string cacheKeyStartsWith)
```


---

#### FindByKey

```csharp
public virtual IEnumerable<object> FindByKey(string keyStartsWith)
```


---

#### FindByKeyTyped&lt;T&gt;

```csharp
public virtual IEnumerable<T> FindByKeyTyped<T>(string keyStartsWith)
```


---

#### Get (1 of 2)

```csharp
public virtual object Get(string cacheKey)
```

---

#### Get (2 of 2)

```csharp
public virtual object Get(string cacheKey, Func<object> factory)
```


---

#### GetTyped&lt;T&gt; (1 of 2)

```csharp
public virtual T GetTyped<T>(string cacheKey)
```

---

#### GetTyped&lt;T&gt; (2 of 2)

```csharp
public virtual T GetTyped<T>(string cacheKey, Func<T> factory)
```


---

#### Set (1 of 2)

```csharp
public virtual void Set(string cacheKey, object cacheValue)
```

---

#### Set (2 of 2)

```csharp
public virtual void Set(string cacheKey, object cacheValue, TimeSpan cacheDuration)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Umbraco.dll -->