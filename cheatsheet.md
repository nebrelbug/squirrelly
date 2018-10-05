## Conditionals
```sqrl
{{if(options.someval === "someothervalue")}}
Display this!
{{#else}}
They don't equal
{{/if}}
```
## Looping over arrays
```sqrl
{{each(options.someArray)}}
The current array item is {{@this}}, the current index is {{@index}}
{{/each}}
```

## Looping over Object

{{#each someObject}}
    Key: {{@key}} Value = {{this}}
{{/each}}
