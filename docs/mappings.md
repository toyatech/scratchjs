# Mappings

| JSON Schema Type | Default Visual Component |
| ---------------- | ------------------------ |
| string           | <input type="text"       |
| number           | <input type="number"     |
| integer          | <input type="integer"    |
| boolean          | <input type="checkbox"   |
| object           | <fieldset                |
| string with enum | <input type="select"     |
| array with enum  | <input type="checkbox"   |
| array of object  | <table                   |
| array with oneOf | <input type="select"     |

# Form example
```
{
  "fieldset": {
    "legend": "Legend:",
    "items": [
      {
        "label": "id",
        "type": "text",
        "format": "url"
      }
    ]
  }
}
```
