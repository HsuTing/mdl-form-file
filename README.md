# File for mdl-form

## Start

Install package:
```
  npm install jquery react react-dom mdl-form mdl-form-file
```

You need to see [mdl-form](https://github.com/HsuTing/mdl-form.git).

## Parameter

- `style` -> change style
- `label` -> name of file
- `isMultiple` -> if you use `isMultiple: true`, it can upload multiple files.
- `isNotRequire` -> if you use `isNotRequire: true`, it can be empty.
- `change`(function) -> you can do something when file is uploaded. `1st` argument is this component value.

## Example

```
{   
  'id': 'component_id',
  'label': 'Label',
  'style': {'color': 'red'},
  'isMultiple': true,
  'isNotRequire': true
}
```
