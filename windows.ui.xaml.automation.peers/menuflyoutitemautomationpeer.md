---
-api-id: T:Windows.UI.Xaml.Automation.Peers.MenuFlyoutItemAutomationPeer
-api-type: winrt class
---

<!-- Class syntax.
public class MenuFlyoutItemAutomationPeer : Windows.UI.Xaml.Automation.Peers.FrameworkElementAutomationPeer, Windows.UI.Xaml.Automation.Peers.IMenuFlyoutItemAutomationPeer, Windows.UI.Xaml.Automation.Provider.IInvokeProvider
-->

# Windows.UI.Xaml.Automation.Peers.MenuFlyoutItemAutomationPeer

## -description
Exposes [MenuFlyoutItem](../windows.ui.xaml.controls/menuflyoutitem.md) types to Microsoft UI Automation.

## -remarks
The Windows Runtime  [MenuFlyoutItem](../windows.ui.xaml.controls/menuflyoutitem.md) class creates a new [MenuFlyoutItemAutomationPeer](menuflyoutitemautomationpeer.md) as its [OnCreateAutomationPeer](../windows.ui.xaml/uielement_oncreateautomationpeer_1478162674.md) definition. Derive your automation peer from [MenuFlyoutItemAutomationPeer](menuflyoutitemautomationpeer.md) if you are deriving a custom class from [MenuFlyoutItem](../windows.ui.xaml.controls/menuflyoutitem.md) and want to add automation support for additional features that you enabled in your custom class. Then override [OnCreateAutomationPeer](../windows.ui.xaml/uielement_oncreateautomationpeer_1478162674.md) so that it returns your custom peer.

### Default peer implementation and overrides in **MenuFlyoutItemAutomationPeer**

[MenuFlyoutItemAutomationPeer](menuflyoutitemautomationpeer.md) has overrides of **Core** methods such that the associated [AutomationPeer](automationpeer.md) methods provide peer-specific information to a Microsoft UI Automation client.

+ [GetPattern](automationpeer_getpattern_2046576749.md) reports that the peer provides pattern support for [PatternInterface.Invoke](patterninterface.md) ([IInvokeProvider](https://msdn.microsoft.com/library/e522b8d5-c6f6-4f71-a8c8-4332f2824f72)).
+ [GetClassName](automationpeer_getclassname_614238974.md) returns "MenuFlyoutItem".
+ [GetAutomationControlType](automationpeer_getautomationcontroltype_1156384152.md) returns [AutomationControlType.MenuItem](automationcontroltype.md).
The peer also has other behaviors that are provided by the base [FrameworkElementAutomationPeer](frameworkelementautomationpeer.md) class. For more info, see "Base implementation in FrameworkElementAutomationPeer" section of [Custom automation peers](https://msdn.microsoft.com/library/aa8da53b-fe6e-40ac-9f0a-cb09637c87b4).

## -examples

## -see-also
[FrameworkElementAutomationPeer](frameworkelementautomationpeer.md), [IInvokeProvider](../windows.ui.xaml.automation.provider/iinvokeprovider.md), [MenuFlyoutItem](../windows.ui.xaml.controls/menuflyoutitem.md)