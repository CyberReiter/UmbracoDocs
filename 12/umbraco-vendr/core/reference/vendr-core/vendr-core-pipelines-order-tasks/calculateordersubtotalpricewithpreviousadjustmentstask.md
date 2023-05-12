---
title: CalculateOrderSubtotalPriceWithPreviousAdjustmentsTask
description: API reference for CalculateOrderSubtotalPriceWithPreviousAdjustmentsTask in Vendr, the eCommerce solution for Umbraco
---
## CalculateOrderSubtotalPriceWithPreviousAdjustmentsTask

```csharp
public class CalculateOrderSubtotalPriceWithPreviousAdjustmentsTask : 
    PipelineTaskWithTypedArgsBase<OrderCalculationPipelineArgs, OrderCalculation>
```

**Inheritance**

* class [PipelineTaskWithTypedArgsBase&lt;!0,!1&gt;](../../../vendr-common/vendr-common-pipelines/pipelinetaskwithtypedargsbase-2/)

**Namespace**
* [Vendr.Core.Pipelines.Order.Tasks](../)

### Constructors

#### CalculateOrderSubtotalPriceWithPreviousAdjustmentsTask

The default constructor.

```csharp
public CalculateOrderSubtotalPriceWithPreviousAdjustmentsTask()
```


### Methods

#### Execute

```csharp
public override PipelineResult<OrderCalculation> Execute(OrderCalculationPipelineArgs args)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->