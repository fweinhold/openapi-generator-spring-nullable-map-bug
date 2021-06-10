While compiling ...
`$ mwnw compile`

You should get two errors:

- [ERROR] [...]/target/generated-sources/openapi/src/main/java/org/openapitools/model/SomeTypeContainingANullableMap.java:[32,30] incompatible types: cannot infer type arguments for java.util.HashMap<>
- [ERROR]     reason: no instance(s) of type variable(s) K,V exist so that java.util.HashMap<K,V> conforms to @javax.validation.Valid org.openapitools.jackson.nullable.JsonNullable<java.util.Map<java.lang.String,org.openapitools.model.MappedType>>
- [ERROR] [...]/target/generated-sources/openapi/src/main/java/org/openapitools/model/SomeTypeContainingANullableMap.java:[34,14] cannot find symbol
- [ERROR]   symbol:   method put(java.lang.String,org.openapitools.model.MappedType)
