
# Schema for confClasses (Schema)

`ogc.api.features.v1.schemas.confClasses` *v0.1*

This building block corresponds to the schema for an OGC API Features confClasses

[*Status*](http://www.opengis.net/def/status): Under development

## Examples

### Example of conformance class declaration
#### json
```json
{
   "conformsTo": [
      "http://www.opengis.net/spec/ogcapi-features-1/1.0/conf/core",
      "http://www.opengis.net/spec/ogcapi-features-1/1.0/conf/oas30",
      "http://www.opengis.net/spec/ogcapi-features-1/1.0/conf/html",
      "http://www.opengis.net/spec/ogcapi-features-1/1.0/conf/geojson",
      "http://www.opengis.net/spec/ogcapi-features-1/1.0/conf/gmlsf0"
   ]
}

```

## Schema

```yaml
type: object
required:
- conformsTo
properties:
  conformsTo:
    type: array
    items:
      type: string
      example: http://www.opengis.net/spec/ogcapi-features-1/1.0/conf/core

```

Links to the schema:

* YAML version: [schema.yaml](https://rob-metalinkage.github.io/bblocks-ogcapi-features/build/annotated/api/features/v1/schemas/confClasses/schema.json)
* JSON version: [schema.json](https://rob-metalinkage.github.io/bblocks-ogcapi-features/build/annotated/api/features/v1/schemas/confClasses/schema.yaml)

## Sources

* [OGC API Features - Part 1 - Core corrigendum](https://docs.ogc.org/is/17-069r4/17-069r4.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/rob-metalinkage/bblocks-ogcapi-features](https://github.com/rob-metalinkage/bblocks-ogcapi-features)
* Path: `_sources/v1/schemas/confClasses`

