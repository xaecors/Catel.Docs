

+++
title = "BehaviorBase" 
description = ""
weight = 20
generator = "SharpDox.Plugins.Hugo"
+++

Name|Value
---|---
Assembly|Catel.MVVM
Namespace|Catel.Windows.Interactivity
Available on|.NET Framework 4.5, .NET Framework 4.6, Xamarin - iOS

```
public abstract class BehaviorBase<T> : IBehavior, Behavior<T> where T : FrameworkElement 
```

**Base types**
[Behavior]({{< relref "#" >}})

**Base types**

[IBehavior]({{< relref "reference/Catel.MVVM/Catel/Windows/Interactivity/IBehavior.md" >}})

Behavior base class that handles a safe unsubscribe and clean up because the default behavior class does not always call`OnDetaching`. This class also adds some specific features such as ValidateRequiredProperties which is automatically called when the behavior is attached.

#### Type Parameters

**T**
The [IView](#) this behavior should attach to.

## Fields

### IsEnabledProperty

The IsEnabled property registration.

## Properties

### IsAssociatedObjectLoaded

Gets a value indicating whether the is loaded.

### IsEnabled

Gets or sets a value indicating whether this behavior is enabled.

## Methods

