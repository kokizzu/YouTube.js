[youtubei.js](../../../README.md) / [YTNodes](../README.md) / CreatePlaylistDialogFormView

# Class: CreatePlaylistDialogFormView

## Extends

- [`YTNode`](../../Helpers/classes/YTNode.md)

## Constructors

### new CreatePlaylistDialogFormView()

> **new CreatePlaylistDialogFormView**(`data`): [`CreatePlaylistDialogFormView`](CreatePlaylistDialogFormView.md)

#### Parameters

• **data**: [`RawNode`](../../APIResponseTypes/type-aliases/RawNode.md)

#### Returns

[`CreatePlaylistDialogFormView`](CreatePlaylistDialogFormView.md)

#### Overrides

[`YTNode`](../../Helpers/classes/YTNode.md).[`constructor`](../../Helpers/classes/YTNode.md#constructors)

#### Defined in

[src/parser/classes/CreatePlaylistDialogFormView.ts:16](https://github.com/LuanRT/YouTube.js/blob/fc5571629eca037af7de03f4b903da6add1f300b/src/parser/classes/CreatePlaylistDialogFormView.ts#L16)

## Properties

### create\_playlist\_params\_collaboration\_disabled

> **create\_playlist\_params\_collaboration\_disabled**: `string`

#### Defined in

[src/parser/classes/CreatePlaylistDialogFormView.ts:13](https://github.com/LuanRT/YouTube.js/blob/fc5571629eca037af7de03f4b903da6add1f300b/src/parser/classes/CreatePlaylistDialogFormView.ts#L13)

***

### create\_playlist\_params\_collaboration\_enabled

> **create\_playlist\_params\_collaboration\_enabled**: `string`

#### Defined in

[src/parser/classes/CreatePlaylistDialogFormView.ts:12](https://github.com/LuanRT/YouTube.js/blob/fc5571629eca037af7de03f4b903da6add1f300b/src/parser/classes/CreatePlaylistDialogFormView.ts#L12)

***

### disable\_playlist\_collaborate

> **disable\_playlist\_collaborate**: `boolean`

#### Defined in

[src/parser/classes/CreatePlaylistDialogFormView.ts:11](https://github.com/LuanRT/YouTube.js/blob/fc5571629eca037af7de03f4b903da6add1f300b/src/parser/classes/CreatePlaylistDialogFormView.ts#L11)

***

### playlist\_title

> **playlist\_title**: `null` \| [`TextFieldView`](TextFieldView.md)

#### Defined in

[src/parser/classes/CreatePlaylistDialogFormView.ts:9](https://github.com/LuanRT/YouTube.js/blob/fc5571629eca037af7de03f4b903da6add1f300b/src/parser/classes/CreatePlaylistDialogFormView.ts#L9)

***

### playlist\_visibility

> **playlist\_visibility**: `null` \| [`DropdownView`](DropdownView.md)

#### Defined in

[src/parser/classes/CreatePlaylistDialogFormView.ts:10](https://github.com/LuanRT/YouTube.js/blob/fc5571629eca037af7de03f4b903da6add1f300b/src/parser/classes/CreatePlaylistDialogFormView.ts#L10)

***

### type

> `readonly` **type**: `string`

#### Inherited from

[`YTNode`](../../Helpers/classes/YTNode.md).[`type`](../../Helpers/classes/YTNode.md#type)

#### Defined in

[src/parser/helpers.ts:8](https://github.com/LuanRT/YouTube.js/blob/fc5571629eca037af7de03f4b903da6add1f300b/src/parser/helpers.ts#L8)

***

### video\_ids

> **video\_ids**: `string`[]

#### Defined in

[src/parser/classes/CreatePlaylistDialogFormView.ts:14](https://github.com/LuanRT/YouTube.js/blob/fc5571629eca037af7de03f4b903da6add1f300b/src/parser/classes/CreatePlaylistDialogFormView.ts#L14)

***

### type

> `static` **type**: `string` = `'CreatePlaylistDialogFormView'`

#### Overrides

[`YTNode`](../../Helpers/classes/YTNode.md).[`type`](../../Helpers/classes/YTNode.md#type-1)

#### Defined in

[src/parser/classes/CreatePlaylistDialogFormView.ts:7](https://github.com/LuanRT/YouTube.js/blob/fc5571629eca037af7de03f4b903da6add1f300b/src/parser/classes/CreatePlaylistDialogFormView.ts#L7)

## Methods

### as()

> **as**\<`T`, `K`\>(...`types`): `InstanceType`\<`K`\[`number`\]\>

Cast to one of the given types.

#### Type Parameters

• **T** *extends* [`YTNode`](../../Helpers/classes/YTNode.md)

• **K** *extends* [`YTNodeConstructor`](../../Helpers/interfaces/YTNodeConstructor.md)\<`T`\>[]

#### Parameters

• ...**types**: `K`

The types to cast to

#### Returns

`InstanceType`\<`K`\[`number`\]\>

The node cast to one of the given types

#### Throws

If the node is not of the given type

#### Inherited from

[`YTNode`](../../Helpers/classes/YTNode.md).[`as`](../../Helpers/classes/YTNode.md#as)

#### Defined in

[src/parser/helpers.ts:38](https://github.com/LuanRT/YouTube.js/blob/fc5571629eca037af7de03f4b903da6add1f300b/src/parser/helpers.ts#L38)

***

### hasKey()

> **hasKey**\<`T`, `R`\>(`key`): `this is CreatePlaylistDialogFormView & { [k in string]: R }`

Check for a key without asserting the type.

#### Type Parameters

• **T** *extends* `string`

• **R** = `any`

#### Parameters

• **key**: `T`

The key to check

#### Returns

`this is CreatePlaylistDialogFormView & { [k in string]: R }`

Whether the node has the key

#### Inherited from

[`YTNode`](../../Helpers/classes/YTNode.md).[`hasKey`](../../Helpers/classes/YTNode.md#haskey)

#### Defined in

[src/parser/helpers.ts:50](https://github.com/LuanRT/YouTube.js/blob/fc5571629eca037af7de03f4b903da6add1f300b/src/parser/helpers.ts#L50)

***

### is()

> **is**\<`T`, `K`\>(...`types`): `this is InstanceType<K[number]>`

Check if the node is of the given type.

#### Type Parameters

• **T** *extends* [`YTNode`](../../Helpers/classes/YTNode.md)

• **K** *extends* [`YTNodeConstructor`](../../Helpers/interfaces/YTNodeConstructor.md)\<`T`\>[]

#### Parameters

• ...**types**: `K`

The type to check

#### Returns

`this is InstanceType<K[number]>`

whether the node is of the given type

#### Inherited from

[`YTNode`](../../Helpers/classes/YTNode.md).[`is`](../../Helpers/classes/YTNode.md#is)

#### Defined in

[src/parser/helpers.ts:28](https://github.com/LuanRT/YouTube.js/blob/fc5571629eca037af7de03f4b903da6add1f300b/src/parser/helpers.ts#L28)

***

### key()

> **key**\<`T`, `R`\>(`key`): [`Maybe`](../../Helpers/classes/Maybe.md)

Assert that the node has the given key and return it.

#### Type Parameters

• **T** *extends* `string`

• **R** = `any`

#### Parameters

• **key**: `T`

The key to check

#### Returns

[`Maybe`](../../Helpers/classes/Maybe.md)

The value of the key wrapped in a Maybe

#### Throws

If the node does not have the key

#### Inherited from

[`YTNode`](../../Helpers/classes/YTNode.md).[`key`](../../Helpers/classes/YTNode.md#key)

#### Defined in

[src/parser/helpers.ts:60](https://github.com/LuanRT/YouTube.js/blob/fc5571629eca037af7de03f4b903da6add1f300b/src/parser/helpers.ts#L60)