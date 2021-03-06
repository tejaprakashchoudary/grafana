+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "StandardEditorContext"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
+++

## StandardEditorContext interface

<b>Signature</b>

```typescript
export interface StandardEditorContext<TOptions> 
```
<b>Import</b>

```typescript
import { StandardEditorContext } from '@grafana/data';
```
<b>Properties</b>

|  Property | Type | Description |
|  --- | --- | --- |
|  [data](#data-property) | <code>DataFrame[]</code> |  |
|  [getSuggestions](#getsuggestions-property) | <code>(scope?: VariableSuggestionsScope) =&gt; VariableSuggestion[]</code> |  |
|  [options](#options-property) | <code>TOptions</code> |  |
|  [replaceVariables](#replacevariables-property) | <code>InterpolateFunction</code> |  |

### data property

<b>Signature</b>

```typescript
data?: DataFrame[];
```

### getSuggestions property

<b>Signature</b>

```typescript
getSuggestions?: (scope?: VariableSuggestionsScope) => VariableSuggestion[];
```

### options property

<b>Signature</b>

```typescript
options?: TOptions;
```

### replaceVariables property

<b>Signature</b>

```typescript
replaceVariables?: InterpolateFunction;
```
