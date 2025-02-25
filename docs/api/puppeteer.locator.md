---
sidebar_label: Locator
---

# Locator class

Locators describe a strategy of locating elements and performing an action on them. If the action fails because the element is not ready for the action, the whole operation is retried. Various preconditions for a successful action are checked automatically.

#### Signature:

```typescript
export declare class Locator extends EventEmitter
```

**Extends:** [EventEmitter](./puppeteer.eventemitter.md)

## Constructors

| Constructor                                                                           | Modifiers | Description                                                 |
| ------------------------------------------------------------------------------------- | --------- | ----------------------------------------------------------- |
| [(constructor)(pageOrFrame, selector, options)](./puppeteer.locator._constructor_.md) |           | Constructs a new instance of the <code>Locator</code> class |

## Methods

| Method                                                                                           | Modifiers | Description                                                                                                                                                                                                                              |
| ------------------------------------------------------------------------------------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [click(clickOptions)](./puppeteer.locator.click.md)                                              |           |                                                                                                                                                                                                                                          |
| [fill(value, fillOptions)](./puppeteer.locator.fill.md)                                          |           | Fills out the input identified by the locator using the provided value. The type of the input is determined at runtime and the appropriate fill-out method is chosen based on the type. contenteditable, selector, inputs are supported. |
| [hover(hoverOptions)](./puppeteer.locator.hover.md)                                              |           |                                                                                                                                                                                                                                          |
| [off(eventName, handler)](./puppeteer.locator.off.md)                                            |           |                                                                                                                                                                                                                                          |
| [on(eventName, handler)](./puppeteer.locator.on.md)                                              |           |                                                                                                                                                                                                                                          |
| [once(eventName, handler)](./puppeteer.locator.once.md)                                          |           |                                                                                                                                                                                                                                          |
| [scroll(scrollOptions)](./puppeteer.locator.scroll.md)                                           |           |                                                                                                                                                                                                                                          |
| [setEnsureElementIsInTheViewport(value)](./puppeteer.locator.setensureelementisintheviewport.md) |           |                                                                                                                                                                                                                                          |
| [setTimeout(timeout)](./puppeteer.locator.settimeout.md)                                         |           |                                                                                                                                                                                                                                          |
| [setVisibility(visibility)](./puppeteer.locator.setvisibility.md)                                |           |                                                                                                                                                                                                                                          |
| [setWaitForEnabled(value)](./puppeteer.locator.setwaitforenabled.md)                             |           |                                                                                                                                                                                                                                          |
| [setWaitForStableBoundingBox(value)](./puppeteer.locator.setwaitforstableboundingbox.md)         |           |                                                                                                                                                                                                                                          |
