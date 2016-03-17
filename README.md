# File for mdl-form

## Start

Install package:
```
  npm install mdl-form mdl-form-file react jquery
```

You need to see [mdl-form](https://github.com/HsuTing/mdl-form.git).

## Parameter

- `style` -> change style
- `className` -> class
- `label` -> name of file
- `isMultiple` -> if you use `isMultiple: true`, it can upload multiple files.
- `isNotRequire` -> if you use `isNotRequire: true`, it can be empty.
- `change`(function) -> you can do something when file is uploaded. `1st` argument is this component value.

## Example

```
{   
  'id': 'component_id',
  'label': 'Label',
  'className': 'class',
  'style': {'color': 'red'},
  'isMultiple': true,
  'isNotRequire': true
}
```
