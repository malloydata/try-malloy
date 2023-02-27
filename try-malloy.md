# Try Malloy

Composer let's you dynamically build queries against a data set or run pre-built queries.

## Queries

<!-- malloy-query
  name="By State"
  description="Airports Region Dashboard" 
  model="/try-malloy/airports.malloy"
-->
```malloy
query: by_state is airports -> airports_by_region_dashboard
```

<!-- malloy-query
  name="By State"
  description="Airports By State" 
  model="/try-malloy/airports.malloy"
-->
```malloy
query: by_state is airports -> by_state
```

<!-- malloy-query
  name="By Facility Type"
  description="Airports By Facility Type" 
  model="/try-malloy/airports.malloy"
-->
```malloy
query: by_state is airports -> by_facility_type
```