---
id: mergeForm
title: mergeForm
---

# Function: mergeForm()

```ts
function mergeForm<TFormData, TFormValidator>(baseForm, state): FormApi<NoInfer<TFormData>, NoInfer<TFormValidator>>
```

## Type Parameters

• **TFormData**

• **TFormValidator** *extends* `undefined` \| `Validator`\<`TFormData`, `unknown`\> = `undefined`

## Parameters

• **baseForm**: [`FormApi`](../classes/formapi.md)\<`NoInfer`\<`TFormData`\>, `NoInfer`\<`TFormValidator`\>\>

• **state**: `Partial`\<[`FormState`](../type-aliases/formstate.md)\<`TFormData`\>\>

## Returns

[`FormApi`](../classes/formapi.md)\<`NoInfer`\<`TFormData`\>, `NoInfer`\<`TFormValidator`\>\>

## Defined in

[packages/form-core/src/mergeForm.ts:37](https://github.com/TanStack/form/blob/03de1e83ad6580cff66ab58566f3003d93d4e34d/packages/form-core/src/mergeForm.ts#L37)